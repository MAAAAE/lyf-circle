# Lyf Circle

## description

> Our project uses AI to analyze user preferences and create social gatherings for hotel residents with similar interests. It automates event creation using shared hotel amenities and includes a chat function to strengthen the Lyf community

<img width="313" alt="image" src="https://github.com/user-attachments/assets/bcef7e42-b0b4-4562-b8e9-4299708ee1d9">

<img width="316" alt="image" src="https://github.com/user-attachments/assets/5033a3d9-3c20-4f19-956c-217e74aadc72">

<img width="311" alt="image" src="https://github.com/user-attachments/assets/e78dfc3f-b974-48ba-9100-f7d06365307f">

## features

1. registres via QR survey
2. matching and grouping users who have similar characteristics and hobbies Using **vector embedding**
3. generate and schedule create events in the context of users and hotel amenities using **gpt4o generative model**
4. social chat function
5. gallery that can upload pics for events



# how to start locally?


## FE
```
cd lyf-circle-fe
npm install
npm run dev
```

## BE

```
cd lyf-circle-be
vi README.md

# for using openai 
export SPRING_AI_OPENAI_API_KEY=<INSERT KEY HERE>
# for postgres vector and mongodb
docker compose up -d

mvn clean install
mvn package -DskipTests
java -jar lyf-circle-0.0.1-SNAPSHOT.jar
```
