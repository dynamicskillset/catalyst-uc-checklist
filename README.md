# Universal Credit checklist

This is a checklist web app using the GOV.UK styleguide. It is the result of a Catalyst-funded project running for 11 weeks from January to March 2021.

> This challenge is to prototype and test ways of providing remote support for individuals struggling or failing to make Universal Credit claims online for reasons like a lack of digital or language skills, or mental health issues.

## How to run it on your local machine

We implemented the GOV.UK frontend [using precompiled files](https://frontend.design-system.service.gov.uk/install-using-precompiled-files/#install-using-precompiled-files), therefore we don't need to install any external dependencies. The needed CSS and Js live on the [assets](https://github.com/dynamicskillset/catalyst-uc-checklist/blob/master/assets) folder.

To clone the repository on your machine type the following line in your terminal:

```bash
git clone https://github.com/dynamicskillset/catalyst-uc-checklist.git
```
Then simply open the `index.html` with your favourited browser.

## How we built it

We tried to follow as much as possible the [GOV.UK design system](https://design-system.service.gov.uk/). 

To save the checked items on local storage and to switch languages based on the url params it has been used [Alpine.js](https://github.com/alpinejs/alpine).

### GOV.UK components used:

- [Header](https://design-system.service.gov.uk/components/header/)
- [Accordion](https://design-system.service.gov.uk/components/accordion/)
- [Details](https://design-system.service.gov.uk/components/details/)
- [Button](https://design-system.service.gov.uk/components/button/)
- [Checkbox](https://design-system.service.gov.uk/components/checkboxes/)
- [Phase banner](https://design-system.service.gov.uk/components/phase-banner/)
- [Footer](https://design-system.service.gov.uk/components/footer/)


## License

Licensed under the GNU LGPL license, see [LICENSE.md](https://github.com/dynamicskillset/catalyst-uc-checklist/blob/master/LICENSE) for details.
