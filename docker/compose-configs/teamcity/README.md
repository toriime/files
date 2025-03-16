<p align="center">
    <br />
    <a href="https://rapier.tabitabi.dev">
        <img src="../../../assets/wordmark.svg" alt="WordMark" width="230" />
    </a>
    <br />
    <br />
    <a href="https://discord.gg/wKumgdQrWy">
        <img src="https://img.shields.io/discord/1139991588324507708?color=5865F2&logo=discord&label=Discord" alt="Discord Server" />
    </a>
</p>

# About

Ready to use docker compose configuration for [TeamCity](https://www.jetbrains.com/teamcity/) CI/CD server.

The config includes:
- TeamCity server
- PostgreSQL database for the TeamCity server
- Traefik reverse proxy routing to the TeamCity server
- TeamCity agent

Important: Make sure to change the email address for acme challenge in the `traefik/traefik.yml` file.