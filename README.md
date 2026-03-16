# CST8915 Lab 4: Introduction to Docker

**Student Name**: IDRIS JOVIAL SOP NWABO

**Student ID**: 041199877

**Course**: CST8915 Full Stack Cloud Native Development

**Semester**: Winter 2026


---

## Demo Video

🎥 [Watch Demo Video](https://www.youtube.com/watch?v=YLPOMGwnmkA)

---

## Reflection Questions

 - What are the main differences between a Docker image and a Docker container? 
    #### Answer: Docker image is a layered stack template used to run a docker container. When running a Docker image, it become a docker container.
 
 - Explain how Docker's layered architecture improves efficiency.
    #### Answer: Docker's layered architecture builds images as stacked, immutable layers from Dockerfile instructions, enabling significant efficiency gains through reuse and minimal duplication.
 
 - Why does each container get its own writable layer? 
    #### Answer: When a container runs, it adds a writable layer on top of the existing image layers. This allow the container to modify, create, or delete files without affecting the original images.
 
 - What are the benefits of using Docker Compose over running containers individually?
    #### Answer: Docker compose help to run multi-container Docker applications. It simplifies managing multiple containers and their relationships in a single docker-compose.yml file. 
    
    
---

## Challenges and Learnings (Optional)


---

## Acknowledgments

[Optional: Credit any resources, documentation, or people who helped you]
