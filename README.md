# [Vue Material Dashboard PRO](https://demos.creative-tim.com/vue-material-dashboard-pro) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/home?status=Vue%20Material%20Dashboard%20PRO%20by%20Creative%20Tim%20https%3A//demos.creative-tim.com/vue-material-dashboard-pro%20via%20%40CreativeTim)


![version](https://img.shields.io/badge/version-1.0.1-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-vue-material-dashboard-pro.svg)](https://github.com/creativetimofficial/ct-vue-material-dashboard-pro/issues?q=is%3Aopen+is%3Aissue) [![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-vue-material-dashboard-pro.svg?maxAge=259200)](https://github.com/creativetimofficial/ct-vue-material-dashboard-pro/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim/material-dashboard) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Product Gif](https://s3.amazonaws.com/creativetim_bucket/github/gif/vue-material-dashboard-pro.gif)

Vue Material Dashboard PRO is a beautiful resource built over [Vue Material](https://vuematerial.io/) and [Vuejs](https://vuejs.org/v2/guide/). It will help you get started developing dashboards in no time. Vue Material Dashboard PRO is the official Vuejs version of the Original [Material Dashboard](https://www.creative-tim.com/product/material-dashboard). Using the Dashboard is pretty simple but requires basic knowledge of Javascript, [Vuejs](https://vuejs.org/v2/guide/) and [Vue Router](https://router.vuejs.org/en/).

We have created it thinking about things you actually need in a dashboard. Vue Material Dashboard PRO contains handpicked and optimised Vuejs plugins. Everything is designed to fit with one another. As you will be able to see, the dashboard you can access on Creative Tim is a customisation of this product.

Let us know what you think and what we can improve below. And good luck with development!


#### Special thanks
During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:
- [Chartist](https://gionkunz.github.io/chartist-js/) for the wonderful charts
- [Tristan Edwards](https://twitter.com/t4t5) for the [Sweet Alert2](https://sweetalert2.github.io/)
- Kirill Lebedev for [jVector Maps](http://jvectormap.com/)


Let us know your thoughts below. And good luck with development!

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions

[<img src="https://s3.amazonaws.com/creativetim_bucket/github/html.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/react.svg" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-react)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/angular.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-angular2)


| Vue | React | Angular | HTML |
| --- | --- | --- | --- |
| [![Vue Material Dashboard Pro HTML](https://s3.amazonaws.com/creativetim_bucket/products/87/thumb/opt_mdp_vue_thumbnail.jpg)](https://www.creative-tim.com/product/vue-material-dashboard-pro) | [![Material Dashboard Pro React](https://s3.amazonaws.com/creativetim_bucket/products/80/thumb/opt_mdp_react_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro-react)  | [![Material Dashboard Pro Angular](https://s3.amazonaws.com/creativetim_bucket/products/55/thumb/opt_mdp_angular_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro-angular2) | [![Material Dashboard Pro HTML](https://s3.amazonaws.com/creativetim_bucket/products/51/thumb/opt_mdp_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro)

## Demo

- [Start page](https://demos.creative-tim.com/vue-material-dashboard-pro)
- [Widgets page](https://demos.creative-tim.com/vue-material-dashboard-pro/#/widgets)
- [Tables page ](https://demos.creative-tim.com/vue-material-dashboard-pro/#/table-list/extended)
- [Maps Page](https://demos.creative-tim.com/vue-material-dashboard-pro/#/maps/google)
- [Notifications page](https://demos.creative-tim.com/vue-material-dashboard-pro/#/components/notifications)
- [Charts page](https://demos.creative-tim.com/vue-material-dashboard-pro/#/charts)

[View More](https://demos.creative-tim.com/vue-material-dashboard-pro).


## Quick start

Quick start options:

- Buy from [Creative Tim](https://www.creative-tim.com/product/vue-material-dashboard-pro)


## Documentation
The documentation for the Material Dashboard Pro is hosted at our [website](https://demos.creative-tim.com/vue-material-dashboard-pro/documentation).


## File Structure

Within the download you'll find the following directories and files:

```
vue-material-dashboard-pro/
├── README.md
├── package.json
├── public
│   ├── img
│   │   ├── faces
│   │   └── flags
│   └── index.html
├── src
│   ├── App.vue
│   ├── assets
│   │   ├── css
│   │   └── scss
│   │       ├── material-dashboard.scss
│   │       └── md
│   ├── components
│   │   ├── AnimatedNumber.vue
│   │   ├── Badge.vue
│   │   ├── Cards
│   │   │   ├── ChartCard.vue
│   │   │   ├── GlobalSalesCard.vue
│   │   │   ├── LockCard.vue
│   │   │   ├── LoginCard.vue
│   │   │   ├── NavTabsCard.vue
│   │   │   ├── PricingCard.vue
│   │   │   ├── ProductCard.vue
│   │   │   ├── SignupCard.vue
│   │   │   ├── StatsCard.vue
│   │   │   └── TestimonialCard.vue
│   │   ├── Collapse.vue
│   │   ├── Dropdown.vue
│   │   ├── Inputs
│   │   │   └── IconCheckbox.vue
│   │   ├── Modal.vue
│   │   ├── NotificationPlugin
│   │   │   ├── Notification.vue
│   │   │   ├── Notifications.vue
│   │   │   └── index.js
│   │   ├── Pagination.vue
│   │   ├── SidebarPlugin
│   │   │   ├── SideBar.vue
│   │   │   ├── SidebarItem.vue
│   │   │   └── index.js
│   │   ├── Slider.vue
│   │   ├── Tables
│   │   │   └── GlobalSalesTable.vue
│   │   ├── Tabs.vue
│   │   ├── Timeline
│   │   │   ├── TimeLine.vue
│   │   │   └── TimeLineItem.vue
│   │   ├── Wizard
│   │   │   ├── Wizard.vue
│   │   │   ├── WizardTab.vue
│   │   │   └── throttle.js
│   │   ├── WorldMap
│   │   │   ├── AsyncWorldMap.vue
│   │   │   ├── WorldMap.vue
│   │   │   └── world_map.js
│   │   └── index.js
│   ├── globalComponents.js
│   ├── globalDirectives.js
│   ├── main.js
│   ├── material-dashboard.js
│   ├── pages
│   │   ├── Dashboard
│   │   │   ├── Calendar.vue
│   │   │   ├── Charts.vue
│   │   │   ├── Components
│   │   │   │   ├── Buttons.vue
│   │   │   │   ├── GridSystem.vue
│   │   │   │   ├── Icons.vue
│   │   │   │   ├── Notifications.vue
│   │   │   │   ├── Panels.vue
│   │   │   │   ├── SweetAlert.vue
│   │   │   │   └── Typography.vue
│   │   │   ├── Dashboard.vue
│   │   │   ├── Forms
│   │   │   │   ├── ExtendedForms.vue
│   │   │   │   ├── RegularForms.vue
│   │   │   │   ├── ValidationForms
│   │   │   │   │   ├── LoginForm.vue
│   │   │   │   │   ├── RangeValidationForm.vue
│   │   │   │   │   ├── RegisterForm.vue
│   │   │   │   │   └── TypeValidationForm.vue
│   │   │   │   ├── ValidationForms.vue
│   │   │   │   ├── Wizard
│   │   │   │   │   ├── FirstStep.vue
│   │   │   │   │   ├── SecondStep.vue
│   │   │   │   │   └── ThirdStep.vue
│   │   │   │   └── Wizard.vue
│   │   │   ├── Layout
│   │   │   │   ├── Content.vue
│   │   │   │   ├── ContentFooter.vue
│   │   │   │   ├── DashboardLayout.vue
│   │   │   │   ├── Extra
│   │   │   │   │   ├── MobileMenu.vue
│   │   │   │   │   └── UserMenu.vue
│   │   │   │   └── TopNavbar.vue
│   │   │   ├── Maps
│   │   │   │   ├── API_KEY.js
│   │   │   │   ├── FullScreenMap.vue
│   │   │   │   ├── GoogleMaps.vue
│   │   │   │   ├── VectorMaps.vue
│   │   │   │   ├── WorldMap.vue
│   │   │   │   └── world_map.js
│   │   │   ├── Pages
│   │   │   │   ├── AuthLayout.vue
│   │   │   │   ├── Lock.vue
│   │   │   │   ├── Login.vue
│   │   │   │   ├── Pricing.vue
│   │   │   │   ├── Register.vue
│   │   │   │   ├── RtlSupport.vue
│   │   │   │   ├── TimeLinePage.vue
│   │   │   │   ├── UserProfile
│   │   │   │   │   ├── EditProfileForm.vue
│   │   │   │   │   └── UserCard.vue
│   │   │   │   └── UserProfile.vue
│   │   │   ├── Tables
│   │   │   │   ├── ExtendedTables.vue
│   │   │   │   ├── PaginatedTables.vue
│   │   │   │   ├── RegularTables.vue
│   │   │   │   └── users.js
│   │   │   └── Widgets.vue
│   │   ├── FixedPlugin.vue
│   │   └── index.js
│   ├── polyfills.js
│   └── routes
│       └── routes.js
└── vue.config.js

```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Resources
- [Live Preview](https://demos.creative-tim.com/vue-material-dashboard-pro)
- Buy Page: https://www.creative-tim.com/product/vue-material-dashboard-pro
- Documentation is [here](https://demos.creative-tim.com/vue-material-dashboard-pro/documentation)
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-vue-material-dashboard-pro/issues)
- Vue Material Dashboard - [demo](https://www.creative-tim.com/product/vue-material-dashboard?ref=github-md-pro)
- For Front End Development - [Material Kit Pro ](https://www.creative-tim.com/product/material-kit-pro?ref=github-md-pro)

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Material Dashboard Pro. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Dashboard Pro. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2018 Creative Tim (https://www.creative-tim.com)
- Creative Tim [license](https://www.creative-tim.com/license)

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim

- [Vue products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
