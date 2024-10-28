# how to start locally?


# fe
```
cd lyf-cycle-fe
npm install
npm run dev
```

# be

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
