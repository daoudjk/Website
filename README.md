Step 1: Identify best web server application to use
    Watch YouTube video: https://www.youtube.com/watch?v=BAMkvEvpol0

Step 2: Download Docker
    https://hub.docker.com/

Step 3: Install WSL 2
    https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package

# Step 4: install the minimalist nginx docker image (alpine)
#    docker pull nginx:1.22.0-alpine

Step 5: create initial website using React with Gatsby template (my focus isn't front-end design)
    https://reactjs.org/docs/create-a-new-react-app.html#gatsby
    https://www.gatsbyjs.com/docs/
    https://www.gatsbyjs.com/starters/hasura/gatsby-gitbook-starter/
    "npx gatsby new gatsby-gitbook-starter https://github.com/hasura/gatsby-gitbook-starter"
    Start the initial web server
        "npm run develop"

Step 5.5: run gatsby template from docker
    navigate to dockerfile directory
    "docker build -t name-of-container ."
    "docker run -dp docker-port:host-port container name"