# Media Queries Lab

TekNews has a great looking website but it was only built for the desktop! Update the website so it can look good on any device.

![Wide default view](./assets/wide-view.png)

---

## Lab Setup

### Getting started

1. Fork and clone this repository.

1. Navigate to the `settings` tab on GitHub, then choose `Pages` from the menu. Configure the `Build and Deployment` to have a `Source` of `Deploy from a branch` and select the `main` branch for deployment. Deployments can take a few minutes, so get started on the lab, and then be sure to check the deployment after you have made a few commits.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

## Instructions

To complete the tests in this lab, you will need to overwrite some styles depending on the width of the screen. If you're unclear about any of the instructions below, remember that you can check the test file to see what exactly is being tested.

### 768px to 1279px

- [ ] Hide the `.splash` section by changing the `display` property to `none`.
- [ ] Set the width of the `main` element to be `90%`.
- [ ] Update the `footer` element so that instead of three columns it is set to have two.

![Medium view](./assets/medium-view.png)

### Less than 768px

- [ ] Update the `header` element so that instead of two columns it is set to have one.
- [ ] Update the `main` element so that instead of two columns it is set to have one.
- [ ] Change the `gap` on the `main` element so that it has a gap between each row of `50px`. The gap between columns should be `0`.
- [ ] Update the `footer` element so it has a padding of `25px` all around.
- [ ] Update the `footer` element so that all of the text inside of it is aligned to the center.
- [ ] Update the `footer` unordered list elements so that none of them have a list-style.
- [ ] Update the `footer` heading so that it no longer has a border along the bottom.

![Narrow view](./assets/narrow-view.png)
