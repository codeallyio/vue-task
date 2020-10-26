# Vue Interview Task

## Background
You want to make the application for displaying launches from the database of SpaceX.
You already downloaded the sample data set of some past launches and put it to `/assets/data-set.vue`.

## TODO

Your task is to display the data from `/assets/data-set.vue`. Every launch should be located in a dedicated HTML container.
They should be positioned in the centre of the screen and lay one under another. Make each container contain three elements:
`mission_name`, `rocket_name` and `launch_date_local`.

You are allowed to configure already existing files. You can also download external packages.

### Format of the data from the assets

[<br/>
&nbsp;&nbsp;{<br/>
&nbsp;&nbsp;&nbsp;&nbsp;mission_name: "CRS-19",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;launch_date_local: "2019-12-05T12:29:23-05:00",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;rocket_name: "Falcon 9",<br/>
&nbsp;&nbsp;},<br/>
&nbsp;&nbsp;{<br/>
&nbsp;&nbsp;&nbsp;&nbsp;mission_name: "Starlink 1",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;launch_date_local: "2019-11-11T09:56:00-05:00",<br/>
&nbsp;&nbsp;&nbsp;&nbsp;rocket_name: "Falcon 9",<br/>
&nbsp;&nbsp;},<br/>
&nbsp;&nbsp;...<br/>
]

### Exemplary layout

![imagea](https://i.imgur.com/bYr01Uq.png)

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### Good Luck!
