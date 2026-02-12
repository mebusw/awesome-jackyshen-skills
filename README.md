# Awesome Trainer Skills

Skills for Consultants, Trainers, Coaches, and Facilitators - an intelligent assistant enhanced with proven methodologies including McKinsey frameworks, Training-from-Back-of-Room, ORID, Bloom's Taxonomy,and NLP patterns.

English | [中文](./README.zh-cn.md)

## Features

This plugin provides specialized skills for:

- 🎯 **Workshop Outlines** - Generate structured training and workshop outlines
- 📝 **WeChat Articles** - Create engaging media articles for WeChat
- 🎬 **Video Scripts** - Generate short video scripts for social media (Douyin, Xiaohongshu)
- 📊 **Quiz Generator** - Create post-training quiz questions based on learning objectives
- 🎓 **Course Scripts** - Generate recorded video course scripts with full curriculum
- 🎤 **Opening Remarks** - Generate classroom opening remarks, icebreakers, and intros
- 📧 **Invitation Emails** - Create training invitation mass emails
- 📚 **Methodologies** - Foundational knowledge: McKinsey, TfBR, ORID, NLP patterns


## Installation

###  Prerequisites
Node.js environment installed
Ability to run `npx bun` commands

### Quick Install (Recommended)

`npx skills add mebusw/awesome-jackyshen-skills`

### Register as Plugin Marketplace
Run the following command in Claude Code:

`/plugin marketplace add mebusw/awesome-jackyshen-skills`

### Install Skills
#### Option 1: Via Browse UI

Select Browse and install plugins
Select awesome-jackyshen-skills
Select the plugin(s) you want to install
Select Install now

#### Option 2: Direct Install
```
# Install specific plugin
/plugin install /jackyshen-design-workshop-outline@awesome-jackyshen-skills
/plugin install /jackyshen-list-methods@awesome-jackyshen-skills
```

#### Option 3: Ask the Agent

Simply tell Claude Code:
> Please install Skills from github.com/mebusw/awesome-jackyshen-skills


### Update Skills
To update skills to the latest version:

1. Run /plugin in Claude Code
2. Switch to Marketplaces tab (use arrow keys or Tab)
3. Select awesome-jackyshen-skills
4. Choose Update marketplace

You can also Enable auto-update to get the latest versions automatically.


## Usage

### Skills

Skills activate automatically based on your questions. Examples:

For explicit invocation, use slash commands:

1. `/jackyshen-design-workshop-outline` - Design workshop outlines
2. `/jackyshen-write-wechat-article` - Write WeChat articles
3. `/jackyshen-gen-short-video-script` - Generate short video scripts
4. `/jackyshen-design-quiz` - Design quiz questions
5. `/jackyshen-gen-recording-course-script` - Generate recording course scripts
6. `/jackyshen-create-opening-remarks` - Create opening remarks
7. `/jackyshen-create-invitation-email` - Create invitation emails for HR
8. `/jackyshen-consult-problem` - Consult problem-solving solutions
9. `/jackyshen-list-methods` - List all methodologies referred

## Methodologies

This plugin incorporates proven frameworks:

- **McKinsey** - Structured problem solving, MECE, hypothesis-driven approach
- **Training-from-Back-of-Room** - Participant-centered learning design
- **ORID** - Objective, Reflective, Interpretive, Decisional facilitation method
- **NLP** - Neuro-Linguistic Programming patterns for communication

## Plugin Structure

```
awesome-jackyshen-skills/
├── .claude-plugin/
│   └── plugin.json          # Plugin manifest
├── skills/                  # Auto-activating skills
│   ├── jackyshen-list-methods/
│   ├── ...
├── examples/                # Example outputs
└── README.md
```

## Contributing

Contributions welcome! Please feel free to submit issues or pull requests.

## License

MIT
