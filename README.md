<<<<<<< HEAD
<h1 align="center">

[![Shuffle Logo](https://github.com/Shuffle/Shuffle/blob/main/frontend/public/images/Shuffle_logo_new.png)](https://shuffler.io)

Shuffle Automation

</h1><h4 align="center">

[Shuffle](https://shuffler.io) is an open source automation platform, built for and by the security professionals. Security operations is complex, but it doesn't have to be. Built to work well with MSSP's and other service providers in mind.

[ Get training ](https://shuffler.io/training)
[_Key Features_](https://shuffler.io/docs/features) —
[_Community & Support_](https://discord.gg/B2CBzUm) —
[ Get training ](https://shuffler.io/training) -
[_Documentation_](https://shuffler.io/docs) —
[_Getting Started_](https://shuffler.io/docs/getting_started) —
[_Development_](https://github.com/shuffle/Shuffle/blob/master/.github/CONTRIBUTING.md) 
[ Set up a demo call ](https://shuffler.io/contact)

Follow us on Twitter at [@shuffleio](https://twitter.com/shuffleio).

</h4>

![Example Shuffle webhook integration](https://github.com/shuffle/Shuffle/blob/main/frontend/src/assets/img/github_shuffle_img.png)

## Try it
* Self-hosted: Check out the [installation guide](https://github.com/shuffle/shuffle/blob/master/.github/install-guide.md)
* Cloud: Register at https://shuffler.io/register and get cooking

Please consider [sponsoring](https://github.com/sponsors/frikky) the project if you want to see more rapid development.
=======
# Shuffle Apps
All public apps are available in the search, engine either in your local instance or on [https://shuffler.io/search?tab=apps](https://shuffler.io/search). This is a repository for apps to be used in [Shuffle](https://github.com/shuffle/shuffle)

**PS:** These apps should be valid with WALKOFF (from NSA), but the SDK is different, meaning you have to change the FIRST line in each Dockerfile (FROM shuffle/shuffle:app_sdk) to make it compatible with Shuffle.

## App Creation 
App creation can be done with the Shuffle App Creator (exports as OpenAPI), with AI Generation, or Python - which makes it possible to connect _literally_ any tool. Always prioritize using the App Creator when applicable, as it makes maintaining an app easier. 

![Shuffle-workflow-categories](https://github.com/shuffle/shuffle-workflows/blob/master/images/categories_circle_dark.png)

### References 
* [App Development Process](https://github.com/shuffle/shuffle-docs/blob/master/handbook/engineering/app_development.md)
* [Python app documentation](https://shuffler.io/docs/app_creation)
* [Apps in progress](https://github.com/shuffle/shuffle-apps/projects/1)

### Categories 
We have defined eight (8) "major" categories of tools that are necessary to any cybersecurity threat. Most security-related tools can fit into one of these eight.
1. [Communication](https://github.com/shuffle/shuffle-apps/issues/26) 		- Any way to chat; WhatsApp, SMS, Email etc. 
2. [Case Management](https://github.com/shuffle/shuffle-apps/issues/22)	- The central hub for operation teams.
3. [SIEM](https://github.com/shuffle/shuffle-apps/issues/21)							- Search engine for logs in an enterprise. Used to find evil.
4. [Assets](https://github.com/shuffle/shuffle-apps/issues/25) 					- Discover endpoint information. Vulnerabilities, owners, departments etc.
5. [IAM](https://github.com/shuffle/shuffle-apps/issues/86)  						- Access Management. Active Directory, Google Workspaces, Single Sign-on etc.
6. [Intelligence](https://github.com/shuffle/shuffle-apps/issues/24) 		- Typically a vendor explaining what you should be looking for.
7. [Network](https://github.com/shuffle/shuffle-apps/issues/27)					- Anything BETWEEN your connected devices. Firewalls, WAF, Switches, Bluetooth...
8. [Eradication](https://github.com/shuffle/shuffle-apps/issues/23) 			- Control machines directly to eradicate evil. Hard and undefined (EDR & AV)

## OpenAPI
Apps in this repository are mostly manually made. Shuffle is striving for standardization and accessability, and our effort is focused on OpenAPI rather than manual work. With this in mind, most app creation that supports REST API's will be continued here.

[Shuffle OpenAPI](https://github.com/frikky/security-openapis)
>>>>>>> 346e296 (Initial commit)

## Support
* [Discord](https://discord.gg/B2CBzUm)
* [Twitter](https://twitter.com/shuffleio)
<<<<<<< HEAD
* [Email](mailto:frikky@shuffler.io)
* [Open issue](https://github.com/shuffle/Shuffle/issues/new)
* [Shuffler.io](https://shuffler.io/contact)

## Blogposts
* [1. Introducing Shuffle](https://medium.com/security-operation-capybara/introducing-shuffle-an-open-source-soar-platform-part-1-58a529de7d12)
* [2. Getting started with Shuffle](https://medium.com/security-operation-capybara/getting-started-with-shuffle-an-open-source-soar-platform-part-2-1d7c67a64244)
* [3. Integrating Shuffle with Virustotal and TheHive](https://medium.com/@Frikkylikeme/integrating-shuffle-with-virustotal-and-thehive-open-source-soar-part-3-8e2e0d3396a9)
* [4. Real-time executions with TheHive, Cortex and MISP](https://medium.com/@Frikkylikeme/indicators-and-webhooks-with-thehive-cortex-and-misp-open-source-soar-part-4-f70cde942e59)

## Documentation
[Documentation](https://shuffler.io/docs) can be found on [https://shuffler.io/docs](https://shuffler.io/docs) and is written here: [https://github.com/shuffle/shuffle-docs](https://github.com/shuffle/shuffle-docs).

### Setting up a local development environment

Please follow the steps mentioned [here](https://github.com/Shuffle/Shuffle/blob/main/.github/install-guide.md#local-development-installation)!

## Related repositories
* OpenAPI apps: [https://github.com/shuffle/security-openapis](https://github.com/shuffle/security-openapis)
* Documentation: [https://github.com/shuffle/shuffle-docs](https://github.com/shuffle/shuffle-docs)
* Workflows: [https://github.com/shuffle/shuffle-workflows](https://github.com/shuffle/shuffle-workflows)
* Python apps: [https://github.com/shuffle/shuffle-apps](https://github.com/shuffle/python-apps)

## Features
* Simple, feature rich [workflow editor](https://shuffler.io/docs/workflows)
* App creator using [OpenAPI](https://github.com/shuffle/OpenAPI-security-definitions)
* Premade apps for your security tools
* Organization and sub-organization control
* Hybrid resource sharing with shuffler.io (optional)

## Website
[https://shuffler.io](https://shuffler.io)

## Contributing
We want to make the world of cybersecurity more accessible and need all the help we can get. Send an email to [support@shuffler](mailto:support@shuffler.io) and we'll make sure to give you any training you may need.

These are the main areas to contribute in:
* Frontend (ReactJS)
* Backend (Golang)
* App Creation (Python & GUI w/OpenAPI)
* Documentation (Markdown)
* Workflow creation (GUI & Conceptualizing) 
* Content Creation (Blogs, videos etc) 

Contributing guidelines are outlined [here](https://github.com/shuffle/Shuffle/blob/master/.github/CONTRIBUTING.md).

## Contributors 
![ICPL logo](https://github.com/Shuffle/Shuffle/blob/main/frontend/src/assets/img/icpl_logo.png)

**Shuffle**
<a href="https://github.com/shuffle/shuffle/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=shuffle/shuffle" />
</a>

=======
* [Email](mailto:support@shuffler.io)
* [Open issue](https://github.com/shuffle/shuffle/issues/new)
* [Shuffler.io](https://shuffler.io/contact)

## External contributions
>>>>>>> 346e296 (Initial commit)
[**App magicians**](https://github.com/shuffle/shuffle-apps)
<a href="https://github.com/shuffle/shuffle-apps/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=shuffle/shuffle-apps" />
</a>

<<<<<<< HEAD

## License
All modular information related to Shuffle will be under MIT (anyone can use it for whatever purpose), with Shuffle itself using AGPLv3. 

Workflows: MIT
Documentation: MIT
Shuffle backend: AGPLv3 
Apps, specification and App SDK: MIT

## Architecture
![Shuffle Architecture](https://github.com/shuffle/Shuffle/blob/main/frontend/src/assets/img/shuffle_architecture.png)

## Security Contributors: Hall of Fame
[Pushpraj](https://github.com/PushprajPatil) - Reported several issues between July and August 2024

### Repository overview 
Below is the folder structure with a short explanation
```bash
├── README.md				# What you're reading right now
├── backend					# Contains backend related code.
│   ├── go-app 			# The backend golang webserver
│   └── app_sdk			# The SDK used for apps
├── frontend				# Contains frontend code. ReactJS, Material UI and cytoscape
├── functions				# Has execution and extension resources, such as the Wazuh integration
│   ├── onprem				# Code for onprem solutions
│   │   ├── Orborus 	# Distributes execution locations
│   │   ├── Worker		# Runs a workflow
└ docker-compose.yml 	# Used for deployments
```

[Get in touch](https://shuffler.io/contact), send a mail to [frikky@shuffler.io](mailto:frikky@shuffler.io) or poke me on twitter [@frikkylikeme](https://twitter.com/frikkylikeme)
=======
[**OpenAPI creators**](https://github.com/frikky/security-openapis)
<a href="https://github.com/shuffle/shuffle-apps/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=frikky/security-openapis" />
</a>

# License
All apps, workflows and modular parts of Shuffle including our App SDK is under licensed under MIT, meaning you can freely use it anywhere in any way you want.

# Contributing
Contributing guidelines for outlined [here](https://github.com/shuffle/shuffle/blob/master/.github/CONTRIBUTING.md).
>>>>>>> 346e296 (Initial commit)
