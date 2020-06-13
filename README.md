# symphony deliverables
How to build a complex distributed application using state of the art tools

![image](https://user-images.githubusercontent.com/2712405/82606714-873b7d80-9b85-11ea-887d-13b261359300.png)


This repository hosts the Web Application named Symphony as https://adriatic.github.io/symphony - a collection of markdown documents created to be the guidance for the group (to be created) community developers interested in making Strapi the best possible CMS tool.

The project is envisioned as two related parts

### 1. Samples collection

This collection can be described using the loop construct, written for the case of interfacing a strapi based full-stack app to all Idenitity Management service providers (PaaS) of interest (to be defined yet)

```
n-paas = {'passport', 'okta', 'aws-aim', 'auth0', ...}
n-fe-framework = {gatsby, vue, angular, svelte, ...}
while n-paas do
begin
  while n-fe-framework
   begin
    createsample(n-fe-framework. npaas)
   end;
end;
```

***This double loop needs to be written better (I wanted to use "pidgeon pascal", but likely failed***


There is one additional external-most loop that goes over all service providers of interest - not just Identity Management. Please apply this loop mentally as I worry this algorithm would be difficult to grasp.


---

### 2. Real life application using most of the "parts" created in the part 1.

At the moment, I envision to create a great implementation of a hybrid between an images galery, blog, and video collaboration tool. Today, WordPress has a commanding position in that space, so we might use an existing app like **[modula](https://wp-modula.com)** as inspiration.

Check **[Project Symphony - Application Model](https://adriatic.github.io/symphony/model/)** for more information




