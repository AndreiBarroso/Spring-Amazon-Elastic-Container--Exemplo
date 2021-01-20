# springboot-docker-ecs

Execute sua imagem Docker no AWS ECS (Elastic Container Service)

### Comandos necessários

- Crie uma imagem do Docker.

		mvn spring-boot:build-image
   
- Execute a imagem do Docker.

		docker run --tty --publish 8080:8080 <image-name>
    
- Tag Docker Image

		docker tag <image-name> tag-name/<image-name>
    
- Envie a imagem do Docker para o Docker Hub

		docker push tag-name/<image-name>
		
- Fluxo de Aplicação 



