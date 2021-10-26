# interview-eng-i

## Getting Started
In order to run this application and complete the specified tasks, please complete the following setup tasks:

### 1. Clone this repository
Clone this repository into your personal Github account.

### 2. Create an account on [Gitpod](https://www.gitpod.io/)
Using the Github account used in the previous step, create a free account on Gitpod.

### 3. Open the repository in a Gitpod workspace
To open the newly cloned repository into a Gitpod workspace, simply navigate to your repo's Github page, prefix the URL with `gitpod.io/#/`, and press Enter. You should be redirected to Gitpod and see some setup taking place.

For additional information on starting your first workspace, please see [this documentation](https://www.gitpod.io/docs/getting-started#start-your-first-workspace).

Example URL: `gitpod.io/#/https://github.com/{github_account_name}/interview-eng-i`

### 4. Install application dependencies
Once the setup from the previous step is complete, you should be redirected to an in-browser version of Visual Studio Code. Additionally, a termnial should have automatically opened and started to install the application's dependencies.

Once the application's dependencies are installed, the start script will execute and open your application in a browser preview tab in Visual Studio Code.

You're now ready to begin your tasks!

## Tasks
### 1. Fetch and render images in the `ImageCarousel` component
Using the supplied API endpoint listed in the resources section below, fetch and display the results in the 'ImageCarousel' component. This component and its images should be visible on the homepage.

Note: The project comes configured with [axios](https://www.npmjs.com/package/axios) as a helpful HTTP client, as well as [React Responsive Carousel](https://www.npmjs.com/package/react-responsive-carousel) to handle the core carousel functionality.

### 2. Extend `Carousel` props
Add props to the `ImageCarousel` component that controls the `showThumbs` and `showIndicators` props on the `Carousel` child component.

In your use of the `ImageCarousel` component for Task 1, make sure the thumbnails are not visible, but the indicators are visible.

### 3. Style the `ImageCarousel` component
Using the mockup included in the root level of the project, position and size the `ImageCarousel` component on the page, with considerations for how responsive it is on smaller screen sizes.

### 4. Add a loading indicator
While waiting for the results from the image API to be returned and rendered, display a loading indicator. A spinner image can be found under the `public` directory. The spinner should be displayed at 100% of its size in the middle of the page.

## Resources
- API Endpoint: `https://apodapi.herokuapp.com/search/?search_query=pluto&number=5`