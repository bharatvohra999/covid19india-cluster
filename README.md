# COVID19 India Cluster Network Graph

This is a dashboard of network connections and clusters to track outbreak and transmission COVID19 in India. The primary data source is collected by volunteers at [covid19india.org](https://www.covid19india.org), a crowdsourced database collated from various news as well as government sources. This can be forked and connected to your Google sheet too. The intention of this graph is to open up options for analysis for policy/decision makers so that they can be more strategic in testing cases and deploying resources like ventilators, beds & medicines.

Primary app is at [https://covid19india-network.now.sh](https://covid19india-network.now.sh/).

![enter image description here](https://i.ibb.co/dmNDthW/Screen-Shot-2020-03-19-at-9-15-51-PM.png)

## Roadmap

1.  More precise cluster filters based on state, district, travel abroad etc
2.  NLP based analysis of Notes section to find out relationship info, travel history etc.
3.  Travel history of locations visited of patients, stay time etc.

## Data Sources

#### Patient data :

- Unofficial sources: https://api.rootnet.in/covid19-in/unofficial/sources
- Unofficial patient tracing data: https://api.rootnet.in/covid19-in/unofficial/covid19india.org

Credits : [https://github.com/amodm/api-covid19-in](https://github.com/amodm/api-covid19-in)

### Spreadsheet :

- [https://docs.google.com/spreadsheets/d/1nzXUdaIWC84QipdVGUKTiCSc5xntBbpMpzLm6Si33zk/edit#gid=0](https://docs.google.com/spreadsheets/d/1nzXUdaIWC84QipdVGUKTiCSc5xntBbpMpzLm6Si33zk/edit#gid=0)

Submit new cases [here](https://aka.ms/reportcovid) !

### NLP Extraction From Unstructured Notes :

Credits : [https://github.com/NirantK/coronaIndia](https://github.com/NirantK/coronaIndia)

#### Credits

- Awesome team at [covid19india.org](https://www.covid19india.org/)

## Customizing

This app can be hooked to any google sheets based database. Is currently based on [covid19india.org](<[https://docs.google.com/spreadsheets/d/1nzXUdaIWC84QipdVGUKTiCSc5xntBbpMpzLm6Si33zk/edit#gid=0](https://docs.google.com/spreadsheets/d/1nzXUdaIWC84QipdVGUKTiCSc5xntBbpMpzLm6Si33zk/edit#gid=0)>) live crowdsourced patient database. Edit client_secrets.json and modify the endpoint in the /api folder to hook it to your own, then deploy to zeit.co to have it working online.

## Issues

Submit an issue or feature request at [issues](https://www.covid19india.org/) or contact the maintainers.

## Maintainers

- [sibeshkar](https://github.com/sibeshkar)
- [someshkar](https://github.com/someshkar)

## Contributing

### Install packages :

```bash

npm install

# or

yarn install

```

### Run Development server with hot-reloading:

```bash

npm run dev

# or

yarn dev

#or

// if you have now CLI

now dev

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Deploy on ZEIT Now

The easiest way to deploy this app is to use the [ZEIT Now Platform](https://zeit.co/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) .
# COVID-19-TRACKER-INDIA
it is a web API covid-19 website.

# Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.

Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment.  Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.

The best way to prevent and slow down transmission is be well informed about the COVID-19 virus, the disease it causes and how it spreads. Protect yourself and others from infection by washing your hands or using an alcohol based rub frequently and not touching your face. 

The COVID-19 virus spreads primarily through droplets of saliva or discharge from the nose when an infected person coughs or sneezes, so it’s important that you also practice respiratory etiquette (for example, by coughing into a flexed elbow).

At this time, there are no specific vaccines or treatments for COVID-19. However, there are many ongoing clinical trials evaluating potential treatments. WHO will continue to provide updated information as soon as clinical findings become available.

# Stay informed:
1. Protect yourself: advice for the public
2. Myth busters
3. Questions and answers
4. Situation reports
5. All information on the COVID-19 outbreak

# To prevent infection and to slow transmission of COVID-19, do the following:
1. Wash your hands regularly with soap and water, or clean them with alcohol-based hand rub.
2. Maintain at least 1 metre distance between you and people coughing or sneezing.
3. Avoid touching your face.
4. Cover your mouth and nose when coughing or sneezing.
5. Stay home if you feel unwell.
6. Refrain from smoking and other activities that weaken the lungs.
7. Practice physical distancing by avoiding unnecessary travel and staying away from large groups of people.


COVID-19 affects different people in different ways. Most infected people will develop mild to moderate illness and recover without hospitalization.

# Most common symptoms:
1. fever.
2. dry cough.
3. tiredness.
4. Less common symptoms:

# aches and pains.
1. sore throat.
2. diarrhoea.
3. conjunctivitis.
4. headache.
5. loss of taste or smell.
6. a rash on skin, or discolouration of fingers or toes.

# Serious symptoms:
1. difficulty breathing or shortness of breath.
2. chest pain or pressure.
3. loss of speech or movement.
4. Seek immediate medical attention if you have serious symptoms.  Always call before visiting your doctor or health facility. 

People with mild symptoms who are otherwise healthy should manage their symptoms at home. 

On average it takes 5–6 days from when someone is infected with the virus for symptoms to show, however it can take up to 14 days. 
