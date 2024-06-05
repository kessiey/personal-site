# Yaw Owusu Kessie - Personal Site

## Project Overview
The Yaw Owusu Kessie Personal Site is a comprehensive web platform built using a microservices architecture. It leverages modern cloud technologies to offer a seamless and interactive experience for visitors. The site consists of four distinct applications: the main site, blog, cloud resume, and games. Each application is deployed as a separate microservice, ensuring modularity, scalability, and ease of maintenance.

### Main Site
The main site serves as the central hub, providing information about Yaw Owusu Kessie, his projects, skills, and contact details. It offers a visually appealing and user-friendly interface designed to engage visitors and showcase his work effectively.

### Blog
The blog section hosts a collection of articles, tutorials, and insights authored by Yaw Owusu Kessie. It provides valuable content on various topics, including technology, entrepreneurship, and personal development. Visitors can explore, read, and engage with the latest blog posts, fostering knowledge sharing and community interaction.

### Cloud Resume
The cloud resume is an innovative approach to presenting Yaw Owusu Kessie's professional profile. It offers a dynamic and interactive resume hosted on the cloud, accessible from anywhere with an internet connection. This modern resume format allows for easy updates, customization, and sharing, making it an effective tool for networking and career advancement.

### Games
The games section offers a collection of interactive games and entertainment experiences. Visitors can enjoy casual gaming sessions, challenge friends, and explore new gaming concepts. This section adds an element of fun and engagement to the site, appealing to a diverse audience of all ages.

## Key Features
- **Microservices Architecture**: Each application is deployed as a separate microservice, enabling independent development, deployment, and scalability.
- **Managed Database**: The blog frontend is connected to a managed Amazon RDS instance, ensuring reliable and scalable database management.
- **DNS Management**: AWS Route53 is used for DNS management, ensuring efficient and reliable routing of traffic to the respective services.
- **Continuous Deployment**: GitHub Actions automates the deployment process, streamlining updates and ensuring seamless integration of new features.
- **Interactive UI**: The site features a visually appealing and user-friendly interface designed to engage visitors and enhance user experience.
- **Dynamic Content**: Content is regularly updated across all sections, keeping visitors informed and engaged with fresh and relevant information.
- **Scalable Infrastructure**: Leveraging Amazon EKS, the site's infrastructure scales dynamically to handle varying levels of traffic and workload demands.

## Links
- **Main Site**: [kessietechinc.com](https://kessietechinc.com/)
- **Blog**: [blog.kessietechinc.com](https://blog.kessietechinc.com/)
- **Cloud Resume**: [resume.kessietechinc.com](https://resume.kessietechinc.com/)
- **Games**: [games.kessietechinc.com](https://games.kessietechinc.com/)

## Repository Structure
- `.github/workflows/`: Contains GitHub Actions CI/CD configurations for all four applications.
- `blog/`: Contains the blog deployment manifest. 
- `games/`: Contains the game deployment manifest.
- `main-site/`: Contains the main website files, including `index.html`, CSS files, Dockerfile, and deployment manifest.
- `resume-site/`: Contains the cloud resume files, including `index.html`, CSS files, Dockerfile, and deployment manifest.

## Cloud Services Used
- AWS Route53 
- Amazon CloudFront
- Amazon EKS 
- Amazon ECR 
- Amazon RDS
- GitHub Actions.