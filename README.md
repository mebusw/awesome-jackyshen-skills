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

`npx skills add mebusw/mebusw-marketplace`

### Register as Plugin Marketplace
Run the following command in Claude Code:

`/plugin marketplace add mebusw/mebusw-marketplace`

### Install Skills
#### Option 1: Via Browse UI

Select Browse and install plugins
Select awesome-trainer-plugin
Select the plugin(s) you want to install
Select Install now

#### Option 2: Direct Install
```
# Install specific plugin
/plugin install /trainer-design-workshop-outline@awesome-trainer-plugin
/plugin install /trainer-list-methods@awesome-trainer-plugin
```

#### Option 3: Ask the Agent

Simply tell Claude Code:
> Please install Skills from github.com/mebusw/mebusw-marketplace


### Update Skills
To update skills to the latest version:

1. Run /plugin in Claude Code
2. Switch to Marketplaces tab (use arrow keys or Tab)
3. Select mebusw-marketplace
4. Choose Update marketplace

You can also Enable auto-update to get the latest versions automatically.


## Usage

### Skills

Skills activate automatically based on your questions. Examples:

For explicit invocation, use slash commands:

1. `/trainer-design-workshop-outline` - Design workshop outlines
2. `/trainer-write-wechat-article` - Write WeChat articles
3. `/trainer-gen-short-video-script` - Generate short video scripts
4. `/trainer-design-quiz` - Design quiz questions
5. `/trainer-gen-recording-course-script` - Generate recording course scripts
6. `/trainer-create-opening-remarks` - Create opening remarks
7. `/trainer-create-invitation-email` - Create invitation emails for HR
8. `/trainer-consult-problem` - Consult problem-solving solutions
9. `/trainer-list-methods` - List all methodologies referred

## Methodologies

This plugin incorporates proven frameworks:

- **McKinsey** - Structured problem solving, MECE, hypothesis-driven approach
- **Training-from-Back-of-Room** - Participant-centered learning design
- **ORID** - Objective, Reflective, Interpretive, Decisional facilitation method
- **NLP** - Neuro-Linguistic Programming patterns for communication

## Plugin Structure

```
awesome-trainer-skills/
├── .claude-plugin/
│   └── plugin.json          # Plugin manifest
├── skills/                  # Auto-activating skills
│   ├── trainer-list-methods/
│   ├── ...
├── examples/                # Example outputs
└── README.md
```

## Contributing

Contributions welcome! Please feel free to submit issues or pull requests.

## License

MIT
