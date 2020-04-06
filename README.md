<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Online Resume
</h1>

Online cv created based on this template: [gatsby-starter-cv](https://github.com/santosfrancisco/gatsby-starter-cv)
Template changed to include navigation bar and some extra sections and data

## 📷 Preview

![Preview](./preview.png)

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```sh
    # create a new Gatsby site using the default starter
    npx gatsby new my-default-starter https://github.com/ajimenezdev/gatsby-cv
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd my-default-starter/
    yarn develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    \_Note: You'll also see a second link: `http://localhost:8000/___graphql`. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql).\_

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

1.  **Generate production build**

That command will generate a production build on _public_ folder

```sh
   yarn build
```

## Configuration

Update the configuration file with your data. The configuration file is in `data/siteConfig.js`

:warning: NOTE: Please change googleAnalyticsId to your ID. See https://analytics.google.com for details.

> **Skills** is a set of your personal skills and their respective levels ranging from > 0 to 100.
> **jobs** is a set of your work experiences

```js
module.exports = {
  siteTitle: 'Hello, im Alexis :)',
  siteDescription: `This is my personal website`,
  keyWords: ['gatsbyjs', 'react', 'react-native', 'curriculum'],
  authorName: 'Alexis Troncoso Torralbo',
  githubUsername: 'alexhoo',
  authorAvatar: '/images/avatar.jpg',
  authorDescription: `I'm a JS FrontEnd engineer, currently focused in React/React Native development.<br/><br/>
  I worked in multiple stacks (React, AngularJs, .Net, Node ...), environments and types of companies (Startup, medium size and big corporate).<br/><br/>
  I'm currently working as a part of an architecture team mainly for React/ReactNative solutions.</strong>`,
  skills: [
    {
      name: 'HTML',
      level: 85,
    },
    {
      name: 'CSS',
      level: 85,
    },
    {
      name: 'Javascript',
      level: 90,
    },
    {
      name: 'React',
      level: 85,
    },
    {
      name: 'ReactNative',
      level: 80,
    },
    {
      name: 'NodeJs',
      level: 60,
    },
    {
      name: 'Git',
      level: 70,
    },
    {
      name: 'Functional Programming',
      level: 30,
    },
  ],
  jobs: [
    {
      company: 'Opinno',
      begin: {
        month: 'aug',
        year: '2019',
      },
      duration: '9 months',
      location: 'El Puerto de Santa María',
      occupation: 'Senior Frontend Engineer',
      description:
        'Daily working in React / React Native for different developments as well as being part of the arthitecture team defining procedures to achieve our daily goals',
    },
    {
      company: 'United Cuisines',
      begin: {
        month: 'apr',
        year: '2015',
      },
      duration: '4 years and 5 months',
      location: 'Jerez de la Frontera',
      occupation: 'Team Leader Fullstack Javascript developer',
      description:
        'Working as a senior frontend developer in touch with the latest frameworks like React, Redux, Angular, NodeJS ...',
    },
    {
      company: 'Atos',
      begin: {
        month: 'feb',
        year: '2014',
      },
      duration: '1 years and 2 months',
      location: 'Seville',
      occupation: 'Senior Programmer',
      description:
        'Dealing with Vivissimo search/crawler engine tool from IBM to support Airbus developments.',
    },
    {
      company: 'Sadiel',
      begin: {
        month: 'mar',
        year: '2009',
      },
      duration: '3 years and 8 months',
      location: 'El Puerto de Santa María',
      occupation: '.Net Developer',
      description:
        'Support and development of systems and applications for Junta de Andalucía as for private companies',
    },
  ],
  education: [
    {
      school: 'University of Cádiz',
      degree: 'Technical Engineer in Management Computing.',
      field: 'Software Engineering',
      startYear: 2002,
      endYear: 2009,
    },
  ],
  languages: [
    {
      language: 'Spanish',
      level: 'Native tongue',
      code: 'ES',
    },
    {
      language: 'English',
      level: 'Fluid Written & Spoken',
      code: 'GB',
    },
  ],
  social: {
    twitter: 'https://twitter.com/alexhooz',
    linkedin: 'https://www.linkedin.com/in/alexis-troncoso-torralbo/',
    github: 'https://github.com/alexhoo/',
    email: 'alexis.troncoso.torralbo@gmail.com',
  },
  hobbies: [
    {
      name: 'Dogs',
      icon: 'FaBone',
    },

    {
      name: 'Traveling',
      icon: 'FaPlane',
    },
    {
      name: 'Movies & Series',
      icon: 'FaTv',
    },
  ],
  siteUrl: 'https://alexistroncoso.es',
  pathPrefix: '/gatsby-starter-cv', // Note: it must *not* have a trailing slash.
  siteCover: '/images/cover.jpeg',
  googleAnalyticsId: 'UA-4492763-3',
  background_color: '#ffffff',
  theme_color: '#1f8276',
  display: 'minimal-ui',
  icon: 'src/favicon.jpg',
  headerLinks: [
    {
      label: 'About',
      url: 'about',
    },
    {
      label: 'Skills',
      url: 'skills',
    },
    {
      label: 'Experience',
      url: 'experience',
    },
    {
      label: 'Education',
      url: 'education',
    },
    {
      label: 'Hobbies',
      url: 'hobbies',
    },
    // {
    //   label: 'Contact',
    //   url: 'contact',
    // },
  ],
}
```
