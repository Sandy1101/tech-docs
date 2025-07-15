**Terminology**
Backstage is organized into three main components, each catering to different groups of contributors who interact with Backstage in distinct ways.

. Core - This includes the base functionality developed by core developers within the open-source project.
. App - The app represents a deployed instance of a Backstage application, customized and maintained by app developers, typically a productivity team within an organization. It integrates core functionalities with additional plugins.
. Plugins - These provide additional functionalities to enhance the usefulness of your Backstage app. Plugins can be company-specific or open-sourced and reusable. At Spotify, we have over 100 plugins created by more than 50 different teams, significantly enriching the unified developer experience by incorporating contributions from various infrastructure teams.

**Overview**
The following diagram shows how Backstage might look when deployed inside a company which uses the Tech Radar plugin, the Lighthouse plugin, the CircleCI plugin and the software catalog.

There are 3 main components in this architecture:

1. The core Backstage UI
2. The UI plugins and their backing services
3. Databases
Running this architecture in a real environment typically involves containerizing the components. Various commands are provided for accomplishing this.
