# Charm Accessories 2025

Replacement of the Charm Accessories website built in 2020 with modern technology. The demonstration setup for the company 'Nordicmade' based in Norway (https://www.nordicmade.com/) 

The code is a Nextjs/dotnet replacement for the "savoy" Wordpress app built by Nordicmade. The demonstration website is at:

http://3.26.70.15/

The CDK deploys the app as a microservice to an AWS Elastic Container Service (ECS) with the Nextjs frondend code and the dotnet backend API code.

The ECS runs both the Nextjs and dotnet apps (docker containers) on the same task using an EC2 cluster.

The task uses a bridge network for communicating between the containers.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template
# ecs-nordic-cdk

The main part of the infrastructure is shown in the code extract below. It is currently deployed only on Australian AWS and will be slow to load in Europe/Norway.

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/1.png)<kbd>

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/6.png)<kbd>

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/3.png)<kbd>

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/4.png)<kbd>

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/2.png)<kbd>

<kbd>![alt text](https://github.com/mckenzie-mm/charm-access-2025/blob/main/images-readme/5.png)<kbd>

