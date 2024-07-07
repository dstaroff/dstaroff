<style>
:root {
    --grad-opacity: 0.1;
    --grad: linear-gradient(45deg, rgba(0,0,0,calc(0*var(--grad-opacity))) 0%, rgba(153,0,255,calc(1*var(--grad-opacity))) 50%, rgba(0,255,248, calc(2*var(--grad-opacity))) 100%);
    --border: 1vw;
    --offset: 2vw;
}
.grad {
    background: var(--grad);
    background-size: 200%, 200%;
    animation: grad-anim 5s ease-out infinite;
    border-radius: var(--border);
    padding: var(--offset);
    margin: var(--offset);
}
@keyframes grad-anim {
    0%{background-position:0 50%}
    50%{background-position:100% 50%}
    100%{background-position:0 50%}
}
</style>

<div align="center">
    <h1>
        Hi, name is Dmitry
    </h1>
    <h3>
        A software developer with a strong passion to create pretty digital things
    </h3>
    <div class="grad">
        <img src="https://github-profile-trophy.vercel.app/?username=dstaroff&title=Experience,PullRequest,Review,MultiLanguage&theme=algolia&no-frame=true&no-bg=true&margin-w=1&column=-1" alt="Stats" />
    </div>
    <div class="grad">
        <a target="_blank" href="https://golang.org/">
            <img width="50vw" height="auto" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" alt="Go" />
        </a>
        <a target="_blank" href="https://docker.com/">
            <img width="50vw" height="auto" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" />
        </a>
        <a target="_blank" href="https://kubernetes.io/">
            <img width="50vw" height="auto" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" />
        </a>
        <a target="_blank" href="https://helm.sh/">
            <img width="50vw" height="auto" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/helm/helm-original.svg" alt="Helm" />
        </a>
        <a target="_blank" href="https://www.terraform.io/">
            <img width="50vw" height="auto" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/terraform/terraform-original.svg" alt="Terraform" />
        </a>
        <a target="_blank" href="https://ubuntu.com/">
            <img width="50vw" height="auto" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ubuntu/ubuntu-original.svg" alt="Ubuntu" />
        </a>
        <a target="_blank" href="https://www.python.org">
            <img width="50vw" height="auto" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" />
        </a>
    </div>
    <h3>
        See you on
    </h3>
    <p>
        <a target="_blank" href="https://linkedin.com/in/dstarov">
            <img width="50vw" height="auto" align="center" src="https://www.vectorlogo.zone/logos/linkedin/linkedin-tile.svg" alt="LinkedIn" />
        </a>
        <a target="_blank" href="https://instagram.com/dstaroff">
            <img width="50vw" height="auto" align="center" src="https://www.vectorlogo.zone/logos/instagram/instagram-tile.svg" alt="Instagram" />
        </a>
    </p>
    <p>
        <a target="_blank" href="https://buymeacoffee.com/kleach">
            <img width="auto" height="50vw" src="https://cdn.buymeacoffee.com/buttons/v2/default-white.png" alt="Buy me a coffee" />
        </a>
    </p>
</div>
