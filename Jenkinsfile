node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("knpatel5900/kpalpine")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
