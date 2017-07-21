---
name: Public Finance Transparency
short_description: >
  Provide a lean and empowering access of the public budget to citizens and
  local administration.
labels:
  - User Interfaces
  - Open Data
customer: cd33
highlights_order: 1
current_stage: Design & Development
next_stage: Private beta
resources:
  github: 'https://github.com/dtc-innovation/dataviz-finances-gironde'
---

We **design and develop** _open source software_ and _graphic materials_ for the Gironde county in order to illustrate their annual budget and financial report.

The aim is to deliver a **reusable and editorialised datavisualisation** based on an open dataset.

### Public Budget Parser

French counties publish their annual budget and financial report under the **M52 standard**. We designed it to be a **standalone NodeJS and JavaScript library**.

We use the M52 library to **validate**, to **lint** and to help the department of finance **to improve the quality of the dataset**.

### Editorial Focus

We organise **user testing sessions** to get an understanding of possible audience expectations and to validate a few hypothesis.

We facilitate **focus groups** with county agents to reflect their mission and financial report in order to match user expectations.

### Datavisualisation Components

We use **React** and the **Redux** pattern to drive the user interface with data and user interactions.

Editorial content is managed with a collaborative spreadsheet which becomes a datasource of the React application.
