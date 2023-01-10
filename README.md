[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# AutogonAI API Postman

Autogon now offers Postman Collections and Environment for a quicker and easier usage of our RESTful APIs.

## How to import and configure
- Clone the `autogonai-api-postman` repository.

- Click the Import button. On Postman, the button is at the top left: 
	<p align="center"><img src="https://raw.githubusercontent.com/autgonai/autogonai-api-postman/main/assets/1.png" alt="Screenshot of Postman with 'Import' button out at top left."></p>

- On the `Import` pop-up page, select the `Folder` tab. Click the `Choose folder from your computer` button and choose the root folder of the previously cloned repository. 

	<p align="center"><img src="https://raw.githubusercontent.com/autgonai/autogonai-api-postman/main/assets/1.png" alt="Screenshot of Postman, showing the Import screen."></p>

- Select which collections and environments you would like to import and click the `Import` button.

	<p align="center"><img src="https://raw.githubusercontent.com/autgonai/autogonai-api-postman/main/assets/1.png" alt="Screenshot of Postman showing the Import screen after selecting the folder."></p>

- Select the `Environments` tab on the left, choose the environment, and set your API ket by changing the `Current Value` column (see screenshort); (The `Timestamp`, `Signature`, `Initial Value` fields can be left empty as they'll be automatically filled by Postman when sending a request.)
	<p align="center"><img src="https://raw.githubusercontent.com/autgonai/autogonai-api-postman/main/assets/1.png" alt="Screenshot of Postman with showing where the user should fill in their API key."></p>

- Select your newly-added environment from the environment dropdown menu. This is at the top right, to the left of the eye icon.
	<p align="center"><img src="https://raw.githubusercontent.com/autgonai/autogonai-api-postman/main/assets/1.png" alt="Screenshot of Postman showing how imported environments can be selected from a dropdown."></p>


## Postman safety practices
The following practices are advised to secure your account's safety:
- Don't use Collections obtained from an unknown source.
- Review the environment JSON file before its usage.
- Don't use any code that you don't understand.
- When you finish trying out the API, delete your API keys.


## FAQ
**Q:** Why can't I get any response? 

You haven't imported the environoment file or you've imported it but you haven't selected it from the dropdown menu (mentioned in [[How to import and configure]])

**Q**: Error `API-key format invalid.`

Likely causes:
- API key is not set.
- API key is not correct. 
- `X-AUG-KEY` is not selected in your Postman `Headers` tab.

**Q**: Error `Mandatory parameter 'xxxx' was not sent, was empty/null or malformed.`

Please refer to the API documentationn to double check all the mandatory parameters.


## My question isn't here
If you don't find your answer here, please consult our developer community on [Discord](https://discord.gg/bR8Zzrjw6y) for similar questions from the community or open an issue [here](https://github.com/autogonai/autogonai-api-postman/issues)