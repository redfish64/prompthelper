index.html is a serverless webpage that allows the user to create prompt templates for use with quickly interacting with an AI app with the same prompt over and over again.

For example, suppose you are often asking about the grammar of your self-constructed chinese sentences. Then using this webpage you can create a template such as:

    Is this grammatically correct? __a__

and a single variable, "a".

Then you can paste something into the "a" value, such as "我不知道如果他好不好。" and an output window will show

    Is this grammatically correct? 我不知道如果他好不好。

Then just copy the output and paste it into your AI app of choice.

All prompts are saved to local storage in the browser, so you can have your own cache of frequently used prompts. There is no server interaction and everything is stored locally.

It should work on mobile phones as well as desktop. You can also export all your prompts to a textbox and you can then copy the contents to save/use elsewhere. Also you can import prompts, by copying text files into the import prompt textbox. For example, if you copy the contents of chinese_prompts.txt, you can paste it into the app and see some maybe useful prompts.

If you want to add some useful prompts for inclusion into this project, just create a pull request. Any other useful changes or additions are also welcome.

You can try/use it here: https://redfish64.github.io/prompthelper

(Most everything was programmed using an AI. I dont know much about js/html, and besides it fits the theme of this apps purpose to be created that way.)
