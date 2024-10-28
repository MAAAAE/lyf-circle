# Lyf Cycle

## description

> Our project uses AI to analyze user preferences, creating social gathering for hotel residents with similar interests. It automates event creation using shared hotel amenities and includes a chat function to improve lyf community.

<img width="316" alt="image" src="https://github.com/user-attachments/assets/1ef59bed-4d1d-4ee1-93c5-6c25ee46f84d">

## features

1. registres via QR survey
2. matching and grouping users who have similar characteristics and hobbies Using **vector embedding**
3. generate and schedule create events in the context of users and hotel amenities using **gpt4o generative model**
4. social chat function
5. gallery that can upload pics for events



# how to start locally?


## FE
```
cd lyf-cycle-fe
npm install
npm run dev
```

## BE

```
cd lyf-cycle-be
vi README.md

# for using openai 
export SPRING_AI_OPENAI_API_KEY=<INSERT KEY HERE>
# for postgres vector and mongodb
docker compose up -d

mvn clean install
mvn package -DskipTests
java -jar lyf-circle-0.0.1-SNAPSHOT.jar
```
