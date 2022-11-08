# Prof Team
## Launch dev build
```
git clone https://github.com/Skiexx/ProfTeam.git
cd ProfTeam
docker-compose --env-file dev.env -f docker-compose.yml -f docker-compose.dev.yml up -d --build
```