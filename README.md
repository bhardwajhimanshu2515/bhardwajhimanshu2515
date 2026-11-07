# Hi, I'm Himanshu Bhardwaj 👋

**Senior Full-Stack Engineer (MERN)** · React.js · Node.js · System Design · 5+ years building scalable web apps

I build products end to end, and lately I build them **with AI**: shipping real, working tools to real users.

---

## 🚀 Latest: Postline, a Claude connector for LinkedIn

[**Postline**](https://github.com/bhardwajhimanshu2515/postline) lets Claude write, schedule and publish LinkedIn posts after you approve them. Submitted to Claude's Connectors Directory.

- **Post types:** text, images (1–20), MP4 video, PDF carousels, polls, link cards and reshares
- **Scheduling:** up to 59 days ahead. The server publishes on time even when Claude is closed, and retries if LinkedIn is briefly down
- **Edit, delete, list and cancel** posts from a chat
- **Stack:** TypeScript · Cloudflare Workers · OAuth 2.1 (Claude) + LinkedIn OAuth · D1 + KV · cron · Model Context Protocol (MCP)
- **Security:** LinkedIn tokens are encrypted (AES-256-GCM), the scheduler claims due posts atomically so nothing posts twice, and there are 36 end-to-end tests against a fake LinkedIn

🔗 Docs: [postline.bhardwajhimanshu2515.workers.dev](https://postline.bhardwajhimanshu2515.workers.dev/)

---

## 🧠 What I've learned: AI is the same for everyone. Experience isn't.

Everyone has the same AI now. The difference is the person using it:

- **Context:** knowing the users, the limits and what failed before, and telling the AI
- **The right question:** experience tells you what to ask, and what *not* to build
- **Judgment:** spotting the confident answer that's wrong before it ships
- **Taste:** not stopping at the first draft

AI raises the floor. Experience raises the ceiling.

---

## 🛠️ How we shipped a Claude connector in one night

1. **Design:** pick only the APIs LinkedIn allows without partner approval, then plan the tools around them
2. **Build:** a remote MCP server on Cloudflare Workers with an OAuth provider, a LinkedIn sign-in bridge and typed tools with safety annotations
3. **Test:** a local Worker against a mock LinkedIn, covering sign-in, posting, uploads, scheduling and failure cases
4. **Deploy:** GitHub → Cloudflare Workers Builds, with secrets kept in Cloudflare
5. **Verify:** connect it as a custom connector in Claude and publish a real post (a 9-slide carousel)
6. **Release:** a docs page, a privacy policy and reviewer instructions, then submit to the Claude Connectors Directory

---

## ⚡ Technologies

- **Front end:** React, JavaScript/TypeScript, HTML5, CSS3
- **Back end:** Node.js, Express, GraphQL, REST, JWT, Cloudflare Workers
- **Data:** MongoDB, MySQL, PL/SQL, Cloudflare D1/KV
- **AI:** Claude, MCP servers and connectors, prompt and workflow design
- **Also:** system design, Git, Python, Java, C/C++, Selenium, Scrapy

## 👯 Communities

- MERN Full Stack Developer at [The Youth Project (TYP)](https://theyouthproject.in/)

## 📫 Contact

- LinkedIn: [My LinkedIn profile](https://www.linkedin.com/in/himanshu-bhardwaj-mern-stack-developer/)
- Stack Overflow: [My Stack Overflow profile](https://stackoverflow.com/users/story/13917162?view=Cv)

![Himanshu's GitHub stats](https://github-readme-stats.vercel.app/api?username=bhardwajhimanshu2515&show_icons=true&theme=default) <br />
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=bhardwajhimanshu2515)](https://git.io/streak-stats)<br />
