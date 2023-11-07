
## 실습

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

using [degit](https://www.docker.com/)
using [degit](https://hub.docker.com/)
using [degit](https://yalco-temp.netlify.app/)
using [degit](https://yalco-temp.netlify.app/36_docker/)
using [degit](https://gitlab.com/yalco/practice-docker/)






```bash
docker run -it node
docker images
docker ps
docker exec -it pedantic_poitras bash
docker ps -a

--- 전부지우기
docker stop $(docker ps -aq)
docker rm $(docker ps -aq)
docker image prune -a

--- 확인
docker images


-- 한꺼번에 올리기
docker-compose up -d

-- 결과확인
http://127.0.0.1:8080/


docker --version
docker run -it node
docker ps
docker ps -a
docker images

docker rmi -f practice-docker-frontend
docker rmi -f practice-docker-backend
docker rmi -f practice-docker-database
git clone https://gitlab.com/yalco/practice-docker.git
docker-compose up
docker-compose up -d
http://127.0.0.1:8080/


```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*




https://cloudstudying.kr/lectures/475
https://cafe.naver.com/imhongpark
https://github.com/Around-Hub-Studio


[[스프링 부트 입문 13] 링크와 리다이렉트](https://www.youtube.com/watch?v=T_najiNzQGw&list=PLyebPLlVYXCiYdYaWRKgCqvnCFrLEANXt&index=15)
[가장 쉽게 배우는 도커](https://www.youtube.com/watch?v=hWPv9LMlme8)

https://cloudstudying.kr/courses/65
https://jang-sn.tistory.com/27
https://github.com/cheogodzip/hong-myblog/tree/master/src/main/java/com/example/myblog
https://hub.docker.com/repository/create?namespace=ulsanbigboy




[VScode 포터블 모드로 사용하기](https://vscode.tistory.com/entry/VScode-%ED%8F%AC%ED%84%B0%EB%B8%94-%EB%AA%A8%EB%93%9C%EB%A1%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)
[(Docker) 도커 서비스 중단/실행](https://kjun.kr/898)

https://www.lesstif.com/docker/docker-hang-42663946.html
https://www.lesstif.com/docker/docker-hang-42663946.html



https://youngwonhan-family.tistory.com/entry/Docker-container-%EC%A0%95%EC%A7%80-%EC%8B%A4%ED%96%89%EC%9E%AC%EC%8B%A4%ED%96%89-%EB%B0%A9%EB%B2%95-stop-start
https://www.lainyzine.com/ko/article/docker-rm-removing-docker-containers/#docker-container-prune-%EC%A4%91%EC%A7%80%EB%90%9C-%EB%AA%A8%EB%93%A0-%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88%EB%A5%BC-%EC%9D%BC%EA%B4%84-%EC%82%AD%EC%A0%9C%ED%95%98%EA%B8%B0
https://hub.docker.com/billing/plan/update?utm_source=docker&utm_medium=in%20product%20ad&utm_campaign=20-11%20nurture%20desktop%20upgrade%20campaign%20dash&utm_budget=demand

https://login.microsoftonline.com/72f988bf-86f1-41af-91ab-2d7cd011db47/oauth2/authorize?response_type=id_token&client_id=405e80fc-f8e6-40e6-b6b9-e5bcc7e6813e&redirect_uri=https%3A%2F%2Fredirectiontool.trafficmanager.net%2Fam%2Fredirection%2Fhome%3Foptions%3Dhost%3Aaka.ms%26set%3DenableReadOnlyLinks&state=89ea7a4d-b346-4c6e-be11-45a433f4dca3&client-request-id=71d52e15-fd2c-41bd-adb6-e3c4c4607b46&x-client-SKU=Js&x-client-Ver=1.0.15&nonce=dc93aca0-9e75-4a7b-8343-09ff0d3af86e
https://git-scm.com/download/win
https://code.visualstudio.com/docs/?dv=winzip
https://code.visualstudio.com/docs/editor/portable
https://git-scm.com/download/win




cd D:\Docker\WorkSpace\practice-docker
D:\Docker\Bin\Git\bin\git clone https://gitlab.com/yalco/practice-docker.git



CONTAINER ID   IMAGE                      COMMAND                   CREATED          STATUS                        PORTS     NAMES
35ef01fbc32f   practice-docker-frontend   "docker-entrypoint.s…"   15 minutes ago   Exited (0) 11 minutes ago               practice-docker-frontend-1
768f3441d0e6   practice-docker-backend    "python3 backend.py"      15 minutes ago   Exited (137) 10 minutes ago             practice-docker-backend-1
4315a78977f2   practice-docker-database   "docker-entrypoint.s…"   15 minutes ago   Exited (1) 13 minutes ago               practice-docker-database-1



docker rmi -f practice-docker-frontend
docker rmi -f practice-docker-backend
docker rmi -f practice-docker-database






```bash
docker --version
git clone https://gitlab.com/yalco/practice-docker.git
docker run -it node
console.log('Hello World!')
docker images
docker ps
docker exec -it confident_kilby bash
docker ps -a
docker rm `docker ps -a -q`
docker rm -f $(docker ps -aq)

docker stop $(docker ps -aq)
docker system prune -a


---
---
---
cd frontend
docker images
docker build -t frontend.img .
docker images
docker run --name frontend-con -v $(pwd):/home/node/app -p 8080:8080 frontend.img
docker run --name frontend-con -v $(pwd):$(pwd) -p 8080:8080 frontend.img
docker run  frontent.img



$(pwd)


docker images
docker rmi -f practice-docker-frontend
docker rmi -f practice-docker-backend
docker rmi -f practice-docker-database
cd ../database
docker build -t database-img .
docker run --name database-con -it -p 3306:3306 database-img
docker-compose up
docker-compose up -d
http://127.0.0.1:8080/

```

