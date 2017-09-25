# dtc-innovation.org

# Install

![Ruby][] has to be installed on your machine to build the project.

```bash
$ bundle install
```

# Run

```bash
$ bundle exec jekyll serve
```

Content will be available locally at [http://127.0.0.1:4000/]().

# Contribute Content

We use ![Netlify CMS][] to handle the

> https://dtc-innovation.org/admin/

# Data Models

## Customer

| Key | Description |
| --- | --- |
| `name` | -  |
| `url` | Website URL |
| `location` | Main country of the customer |
| `has_logo` | Boolean to indicate if its SVG logo is to be found in `images/customers/customers.svg#<customer-id>` |

- name: Gironde County
- url: https://gironde.fr/
- location: France
- has_logo: false



## Project

To be found in `_projects/*.md`.
Available as a `site.projects` collection.

| Key | Description |
| --- | --- |
| `name` | - |
| `short_description` | - |
| `highlights_order` | Controls ordering on the Home _Project Highlights_ |
| `current_stage` | Definition of done of the current sprint |
| `next_stage` | Expectations about the next project milestone (mid-term) |
| `customer` | Related customer (from within [`_data/customers.yaml`](_data/customers.yaml)) |
| `ressources.website` | Website URL |
| `ressources.github` | GitHub repo URL |

[Ruby]: https://www.ruby-lang.org/
[Netlify CMS]: https://www.netlifycms.org/
