# Project JA 3
> Interact with the mystical conch shell, engage in weekly conversation prompts, and delegate decision-making. V3. Fall 2023.

---

```bash
version: '3.8'

services:
  ja:
    image: lxrbckl/project-ja:latest
    deploy:
      replicas: 1
    environment:
      - TokenOpenAi=
      - Status=
      - Query=

      - TokenDiscord=
      - GuildId=
      - ChannelId=
      - ApplicationId=
```

---

<p align="center">
  
  <img width="155" src="https://i.postimg.cc/0Qz8k5L2/Kyle.jpg">
</p>
<div align="center">
  
  *In loving memory of Kyle, our beloved aquatic friend.*

</div>
