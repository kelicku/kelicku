# 💫 About Me
I've spent the last seven years in the trenches as a senior full-stack and blockchain engineer. My specialty is cutting through the complexity to build robust, scalable solutions—whether that's a sleek web app or a novel smart contract system.

I'm a natural collaborator and a pragmatic problem-solver. I thrive in teams that are building something meaningful and enjoy working directly with clients to make sure what we build not only works but actually moves the needle. I stick around to make sure it's done right.


```Move
impl Default for AboutMe {
    fn default() -> Self {
        Self {
            programming_languages: vec![
                "Javascript", "Solidity", "Rust", "Move", "Dart", "C++", "Python", "Java"
            ],
            ask_me_about: vec![
                "blockchain dapps", "smart contract", "trading bot", "DEX", 
                "web dev", "tech", "app dev"
            ],
            technologies: Technologies {
                full_stack: FullStack {
                    blockchain: vec!["EVM", "SVM", "Hardhat", "GraphQL", "Moralis"],
                    web_dev: vec!["React", "Next", "Node", "Express", "TailwindCSS"],
                },
                mobile_app: MobileApp {
                    cross_platform: vec!["Flutter Development", "Dart"],
                },
                dev_ops: vec!["Azure", "Docker🐳"],
                databases: vec!["mongoDB", "firebase"],
                other_tools: vec!["Git", "Figma", "Postman", "Photoshop"],
            },
            tech_communities: TechCommunities {
                core_team: "Google Developer Student Club",
                mentor: "Microsoft Learn Student Ambassador",
                tech_web_lead: "Ecell, IIITL",
                sessions: "Axios, IIITL",
                co_organizer: "Equinox, Enspire",
            },
            fun_fact: "There are two ways to write error-free programs; only the third one works",
        }
    }
}

```
