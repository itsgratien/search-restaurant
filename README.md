# Search-restaurant

This APP allows to create and search restaurant using slack API. it was implemented using two slack features such as :
* slash commands and 
* interactive messages.

## Prerequisites
* MONGO DB [installation](https://www.mongodb.com/download-center/enterprise)
* Create workspace from [slack](https://www.slack.com) or login to your workspace
* Create [APP](https://api.slack.com/)
* follow steps to enable slack features on App. here is an example on screenshoot below

![Screen Shot 2019-10-09 at 22 52 53](https://user-images.githubusercontent.com/27460888/66519396-8f0f4b80-eae7-11e9-98c8-a2d923db2372.png)

## Usage

### Clone Repo
```
git clone https://github.com/itsgracian/search-restaurant.git
```
### Installation
```
yarn install or npm install
```
### Start development server
```
yarn start:dev or npm run start:dev
```
### Open slack workspace

#### Search restaurant by name using slash command

```
/restaurant nameofrestaurant
```
#### Get all available restaurant

```
/all-restaurant
```

### Add new Restaurant
```
/create-restaurant

```

##### Screenshots
<img width="1155" alt="Screen Shot 2019-10-10 at 13 51 03" src="https://user-images.githubusercontent.com/27460888/66566373-0df69980-eb65-11e9-82bf-8db91dbcb7ea.png">

###### Add new restaurant

![Screen Shot 2019-10-10 at 19 47 51](https://user-images.githubusercontent.com/27460888/66593318-0cde6000-eb97-11e9-9b69-c7e9792e1fe4.png)

## Author

[gratien](https://www.github.com/itsgracian)

## Licence
MIT


