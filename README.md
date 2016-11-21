# nrs-deaths
Numbers of deaths registered in Edinburgh by cause. 

Deaths are generally counted on the basis of the area of usual residence of the deceased if that is in Scotland, otherwise they are counted on the basis of the place of death. However, a death may be allocated to the deceased's former area of residence, if that is in Scotland and the deceased had lived at his/her usual residence for less than 12 months.

Statistics provided by National Records of Scotland:  http://statistics.gov.scot/data/deaths

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nrs-deaths.git
```

Install npm dependencies

```
cd nrs-deaths
npm install
```

Run the API (from the nrs-deaths directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
