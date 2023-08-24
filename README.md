# ward-dashboard

this project contains: 

```sh
├── boundaries - topojson custom maps
├── data - some data is held by dashboard
├── docs
├── README.md
├── style - powerbi theming files
└── ward-dashboard.pbix - power bi file
```

_NOTE on Geography_ currently we are using 2021 output areas (where possible), these are the smallest unit of aggregation, and can be fairly accurately assigned to wards, although there are many [OAs that don't fit perfectly](https://nbviewer.org/github/data-hamlets/census-data/blob/main/notebooks/0.2-lbth-oa-ward-overlaps.ipynb). 

![map showing oas overlapping wards](./docs/oas-overlapping-wards.png)
