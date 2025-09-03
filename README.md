# Icelandic National AI Championship 2025

Welcome to the official repository for the Icelandic National AI Championship! This competition brings together Iceland's brightest minds in artificial intelligence to tackle real-world challenges across three key domains.

## Competition Overview

The championship runs from **March 1 - May 31, 2025** and features three challenging problems spanning reinforcement learning, natural language processing, and computer vision. Teams of up to 4 members will compete for a total prize pool of **1,000,000 ISK**.

## Important Links

- 📱 [Discord Channel](https://discord.gg/iceland-ai-championship) - Join for announcements, Q&A, and community discussion
- 📊 [Live Leaderboard](https://ai-championship.is/leaderboard) - Track your ranking in real-time
- 📧 Contact: ai-championship@iceland.is

## Problems

Explore each challenge in detail:

- [**Reinforcement Learning Problem**](./RL_problem) - Optimize renewable energy distribution across Iceland's power grid
- [**Natural Language Processing Problem**](./NLP_problem) - Build an Icelandic language assistant for tourism
- [**Computer Vision Problem**](./CV_problem) - Detect and classify volcanic activity from satellite imagery

## How to Get a Server

Each team is entitled to **one free server** with the following specifications:
- **GPU**: 1x NVIDIA A100 (40GB)
- **CPU**: 16 vCPUs
- **RAM**: 64 GB
- **Storage**: 500 GB SSD

To claim your server:
1. Register your team at [ai-championship.is/register](https://ai-championship.is/register)
2. Submit your team members' information
3. Receive access credentials within 24 hours
4. Access your server via SSH using provided credentials

**Note**: Additional compute resources can be purchased at discounted rates.

## Submission

Submit your solutions through our automated evaluation system:

1. Package your solution as a Docker container
2. Push to our registry: `docker push registry.ai-championship.is/team-[YOUR_TEAM_ID]/[PROBLEM]:[VERSION]`
3. Submit via the portal: [ai-championship.is/submit](https://ai-championship.is/submit)
4. Your solution will be evaluated automatically

**Submission limits**: 
- Maximum 5 submissions per day per problem
- Final submission deadline: May 31, 2025, 23:59 GMT

## Scoring System

### Ranked Score (RS)
Your position relative to other teams:
```
RS = (N - R + 1) / N × 100
```
Where N = total teams, R = your rank

### Total Score (TS)
Your combined performance across all problems:
```
TS = 0.35 × RS_RL + 0.35 × RS_NLP + 0.30 × RS_CV
```

## Final Evaluation

After the competition closes:
1. **Code Review** (June 1-7): Top 10 teams submit full source code for verification
2. **Private Test Set** (June 8-14): Solutions evaluated on hidden test data
3. **Presentation Day** (June 20): Finalists present their approaches in Reykjavík
4. **Winners Announced** (June 20): Awards ceremony and networking event

## Prizes

- 🥇 **1st Place**: 750,000 ISK + NVIDIA DGX Station
- 🥈 **2nd Place**: 200,000 ISK + High-end workstation
- 🥉 **3rd Place**: 50,000 ISK + Latest GPU

Special category awards for best approach in each problem domain.

## FAQ

**Q: Can international students participate?**  
A: Yes, if you're enrolled in an Icelandic university or have been resident for 6+ months.

**Q: Are pre-trained models allowed?**  
A: Yes, but you must document all external resources and models used.

**Q: Can we use external datasets?**  
A: Only publicly available datasets. Private or proprietary data is prohibited.

**Q: How is plagiarism handled?**  
A: Automated detection + manual review. Violations result in immediate disqualification.

**Q: Can we change team members?**  
A: Changes allowed until March 15, 2025. After that, teams are locked.

**Q: Is there support for beginners?**  
A: Yes! We offer workshops every Saturday and have mentors available on Discord.

## Code of Conduct

We are committed to providing a welcoming and inspiring community for all. Please read our [Code of Conduct](https://ai-championship.is/code-of-conduct) before participating.

## Sponsors

This championship is proudly sponsored by:
- Ministry of Higher Education, Science and Innovation
- Icelandic Centre for Research (Rannís)
- Leading tech companies and research institutions

---

Good luck to all participants! May the best algorithms win! 🚀

*For technical issues, contact: tech-support@ai-championship.is*
