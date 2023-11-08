# EzyButton

You can get EzyButton here: https://assetstore.unity.com/packages/slug/269683
EzyButton Guide

How to Use EzyButton:

using Ezy; is required whenever you would like to use [EzyButton]

Section 1: Button Label / Name: If you don't want to change the default button label, you can leave it empty by using "".
Section 2: Button Description: Similarly, if you want to keep the default description, use "" to leave it blank.
Section 3: Button Color: You can customize the button color by specifying the RGB values on a scale of 0 to 255. 
For example, R: 50, G: 50, B: 50 represents a dark gray color.

Below are some examples and combinations of how to use EzyButton:

Example 1:
To create a Dark Blue Button with the label "Get Random Int" and a description of "Gets a random int between 0 and 10," you can use the following code:

[EzyButton("Get Random Int", "Gets a random int between 0 and 10", 50, 50, 255)]
public int ReturnRandom() { return Random.Range(0, 10); }

Example 2:
To create a Dark Blue button with the label "Save Game" and a description of "Saves the game's data," you can use the following code:

[EzyButton("Save Game", "Saves the game's data", 50, 50, 255)]
public void SaveDataToFile() { // Example code here }

Here are some more options:

[EzyButton]: This creates a plain button using the default method label.
[EzyButton("NewName")]: This creates a plain button with a different name than the default method label.
[EzyButton("", "Description")]: This creates a plain button with the default method label and a description.
[EzyButton("NewName", "Description")]: This creates a plain button with a custom label and description.
[EzyButton("NewName", "Description", 50, 50, 255)]: This creates a plain button with a custom label, description, and color.
[EzyButton(30, "NewName", "Description", 50, 50, 255)]: This creates a plain button with a custom label, description, and color with a spacing of 30 at the bottom.

I hope this format helps you better understand how to use EzyButton!
