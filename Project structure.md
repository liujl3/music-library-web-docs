### Project files

```
│  index.html                       // Homepage, project entrance
│  package.json                     // project dependencies
│  README.md                        // This file, project description
├─build                             // Project completion (webpack) related code
├─config                            // Project development environment configuration
├─src                               // source code
│  │  App.vue                       // Root component of Vue
│  │  main.js                       // Program entry script
│  ├─common
│  │  └─font                        // External font
│  ├─components                     // Vue Components
│  │      Chart.vue                 // Data visualization component
│  │      ContentContainer.vue      // Content layout component
│  │      CurrentManaged.vue        // Display and switch the currently selected person
│  │      Header.vue                // Page header
│  │      Sidebar.vue               // Sidebar navigator
│  │      UserInfo.vue              // Show and edit user information
│  ├─router
│  │      index.js                  // Vue Router configuration
│  └─views                          // Pages, rendered by router-view
│          Analyse.vue              // Display statistical charts
│          Category.vue             // Category-based category management
│          Library.vue              // library base, providing support for Music, Upload and Category, automatically adapting to the public and private library
│          Login.vue                // Login page
│          Manage.vue               // Member management
│          Music.vue                // File management and music-based category management
│          NotFound.vue             // Match any non-existent path
│          People.vue               // Assign people with dementia to carers
│          Upload.vue               // Upload new music file
├─static                            // Static files
└─theme                             // Custom theme of Element-UI
```

### Technology Stack

| Name                                                      | Usage                                                        |
| --------------------------------------------------------- | ------------------------------------------------------------ |
| [webpack](https://github.com/webpack/webpack)             | Resource packaging.                                          |
| [Vue.js](https://github.com/vuejs/vue)                    | Front-end framework.                                         |
| [vue-router](https://github.com/vuejs/vue-router)         | Page router configuration.                                   |
| [vue-cookie](https://github.com/alfhen/vue-cookie#readme) | Read and write cookies, used for authentication.             |
| [axios](https://github.com/axios/axios)                   | Asynchronously call API; Cross-origin access during development. |
| [Element](https://github.com/ElemeFE/element)             | UI Toolkit.                                                  |
| [ECharts](https://github.com/apache/incubator-echarts)    | Data visualization.                                          |
