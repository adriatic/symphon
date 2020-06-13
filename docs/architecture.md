# Architecture

### Introduction
Symphony is primary a teaching tool, intended to cover all application types of interest, on all platforms (Linux, MacOS, Windows), using all distributed services of interest. This approach is a improvement over the current collection of tutorials like Build a blog with React, Strapi and Apollo mostly written by Maxime Castres and defined as:

`tutorials on how to make blogs using Strapi with a lot of frontend frameworks: Gatsby Old, Gatsby new, Next.js, Vue, Nuxt or Angular.`

### Key properties

1. Symphony is a single application
<br>
All current Strapi tutorials describe the process of creation of a blog application on different platforms, using different front end frameworks, different back ends. This can be restated as "use a single small app in different contexts, where each specific element of that set is a separate blog application kept in its own repository. See https://github.com/strapi/strapi-starter-react-blog as an example.
<br><br>
Symphony is a sufficiently complex distributed application, capable of demonstrating the context of all current Strapi samples, and (important) it has a practical value for many Strapi (and other) users - see Symphony application model for more details.
<br><br>
Besides being a single source code application Symphony will be used by Strapi developers as the testbed in the process of creating the official support for many services of interest to Strapi users. The first such service is the Identity Management (aka Authentication and Authorization, which is a misnomer as IM offers a lot more than just Authentication and Authorization).

<p></p><p></p>

***Here follows the sketch of Symphony***