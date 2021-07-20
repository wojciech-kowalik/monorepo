# monorepo based on rush

## rush init   
rush init  
rush build  
rushx start - just start project  

## rush adding new project
rush update —purge  
rush add —package NEW_PROJECT_NAME  
rush build   

## rush deploy
rush init-deploy -p PROJECT_NAME  

## netlify command
npm i -g @microsoft/rush && rush install && rush build && rush deploy --overwrite -p landing && cd common/deploy/apps/landing && rushx build
