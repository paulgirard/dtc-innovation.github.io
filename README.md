# dtc-innovation.github.io


# Data Models

## Customer

| Key | Description
|---
| `name` | -
| `url` | Website URL
| `location` | Main country of the customer
| `has_logo` | Boolean to indicate if its SVG logo is to be found in `images/customers/customers.svg#<customer-id>`

name: Gironde County
url: https://gironde.fr/
location: France
has_logo: false



## Project

To be found in `_projects/*.md`.
Available as a `site.projects` collection.

| Key | Description
|---
| `name` | -
| `short_description` | -
| `highlights_order` | Controls ordering on the Home _Project Highlights_
| `current_stage` | Definition of done of the current sprint
| `next_stage` | Expectations about the next project milestone (mid-term)
| `customers` | A list of related customers (from within [`_data/customers.yaml`](_data/customers.yaml))
| `ressources.website` | Website URL
| `ressources.github` | GitHub repo URL
