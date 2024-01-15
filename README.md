# Microsoft 365 Sample Gallery - System files

Backend control and assets for the [Microsoft 365 Sample Gallery](https://aka.ms/community/samples).

To ensure a consistent approach on how to promote samples, we put together some guidelines that make it easier for you to extend the gallery with your repositories and to streamline the process for maintainers of this repository.

## Guidelines

- Each sample needs to have a README file and screenshot showcasing what the sample is all about – we should not require customers and partners to install the sample before showcasing it. We follow this guidance with the Microsoft 365 samples and Power Platform community samples, so that the barrier of seeing the sample live is as low as possible. We use standard README files for our samples to ensure the quality of them, please see this [example](https://github.com/pnp/sp-dev-fx-webparts/blob/main/templates/README-template.md) for reference.

- Getting a sample to the sample gallery always requires a screenshot(s) – which is good for sparking interest and understanding on the sample – so typically README files contains guidance and input on how to use the sample. Please see this [example](https://github.com/OfficeDev/Microsoft-Teams-Samples/tree/main/samples/app-hello-world/csharp) to see Gif files in action: They are are great for showcasing how the sample actually works without requiring it to be installed.

- When the README and screenshot(s) exists, you will need to create `sample.json` file for your sample in `assets` folder. Please see this [example](https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/app-hello-world/csharp/assets/sample.json) for reference.

- Let us know once you want your repository to be added by raising an [issue](https://github.com/pnp/m365-sample-gallery/issues) so that we can enable your repo to get crawled by our content bot. The bot will then gather the information, images and links you have provided and then surface the sample at the sample gallery. This bot reads all `sample.json` files on a daily basis and then updates the information automatically at the sample portal at [https://aka.ms/community/samples](https://aka.ms/community/samples).

In case you do have any question please raise an issue in this repo, we are happy to help.
