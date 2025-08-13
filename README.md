# Cursor Project Standards

**Version**: 1.0.0  
**Purpose**: Organizational development standards and AI assistance rules for Product Management workflows in structured finance

## 🎯 Overview

This repository provides a comprehensive set of Cursor AI rules and templates for Product Management workflows, specifically designed for structured finance applications. It includes persona-based AI behavior modification, project templates, and development standards.

## �� What's Included

### **Foundation Rules**
- **Core Thinking** (`00-core-thinking.mdc`) - Deep analytical methodology and reasoning frameworks
- **Core Development** (`01-core-development.mdc`) - Systematic development standards and best practices
- **Troubleshooting** (`02-persona-troubleshoot.mdc`) - Diagnostic analysis and problem-solving behavior
- **New Team Member** (`03-persona-new-team-member.mdc`) - Context loading for project onboarding

### **Product Management Workflow Rules**
- **Opportunity Analysis** (`04-persona-opportunity-analysis.mdc`) - Market analysis and business case development
- **Project Management** (`05-persona-project-management.mdc`) - Stakeholder coordination and timeline tracking
- **Requirements Writing** (`06-persona-requirements-writing.mdc`) - User journeys, themes, epics, and stories
- **Version Planning** (`07-persona-version-planning.mdc`) - Release planning and feature prioritization
- **Sprint Planning** (`08-persona-sprint-planning.mdc`) - Kanban methodology and capacity planning

### **Design & Technical Rules**
- **Technical Design** (`09-persona-technical-design.mdc`) - System architecture and implementation planning
- **UX Design** (`10-persona-ux-design.mdc`) - User experience design with Material Design foundation

### **Templates & Tools**
- **Project Status Template** - Standardized project management documentation
- **Lesson Learned Template** - Structured knowledge capture and sharing
- **Project Management Structure** - Organized folder hierarchy for requirements and design

## 🚀 Quick Start

### **Option 1: Clone and Copy**
```bash
# Clone the repository
git clone https://github.com/aeyarr/cursorrules.git

# Copy to your project
cp -r cursorrules/.cursor ./my-project/
cp -r cursorrules/project-management ./my-project/
```

### **Option 2: Direct Download**
1. Download the repository as ZIP
2. Extract `.cursor/` and `project-management/` folders to your project
3. Restart Cursor IDE to load the new rules

### **Option 3: CLI Installation** *(Future)*
```bash
# Install the CLI tool
npm install -g @yourorg/cursor-project-standards

# Apply to new project
cursor-project-cli init my-new-project
```

## 📁 Repository Structure

```
cursorrules/
├── .cursor/
│   ├── rules/                              # AI behavior rules
│   │   ├── 00-core-thinking.mdc           # Analytical methodology
│   │   ├── 01-core-development.mdc        # Development standards
│   │   ├── 02-persona-troubleshoot.mdc    # Problem-solving behavior
│   │   ├── 03-persona-new-team-member.mdc # Context loading
│   │   ├── 04-persona-opportunity-analysis.mdc # Market analysis
│   │   ├── 05-persona-project-management.mdc # Stakeholder coordination
│   │   ├── 06-persona-requirements-writing.mdc # Requirements engineering
│   │   ├── 07-persona-version-planning.mdc # Release planning
│   │   ├── 08-persona-sprint-planning.mdc # Sprint management
│   │   ├── 09-persona-technical-design.mdc # System architecture
│   │   └── 10-persona-ux-design.mdc      # User experience design
│   └── templates/                          # Document templates
│       ├── project-status.md.template     # Project management template
│       └── lesson-learned-template.md     # Knowledge capture template
├── project-management/
│   ├── lessons-learned/                    # Knowledge repository
│   └── README.md                          # PM guidelines
├── README.md                              # This file
└── package.json                           # Distribution metadata
```

## 🎭 Rule Activation

Rules are activated by their specific context:

### **Foundation Rules (Always Available)**
- `00-core-thinking.mdc` - Always applied (`alwaysApply: true`)
- `01-core-development.mdc` - Always applied (`alwaysApply: true`)

### **Persona Rules (Manual Activation)**
- `02-persona-troubleshoot.mdc` - Debugging and issue resolution
- `03-persona-new-team-member.mdc` - Project onboarding and context loading
- `04-persona-opportunity-analysis.mdc` - Market research and business cases
- `05-persona-project-management.mdc` - Stakeholder and timeline coordination
- `06-persona-requirements-writing.mdc` - User stories and requirements documentation
- `07-persona-version-planning.mdc` - Release planning and roadmap development
- `08-persona-sprint-planning.mdc` - Sprint scope and capacity planning
- `09-persona-technical-design.mdc` - System architecture and technical specifications
- `10-persona-ux-design.mdc` - User interface design and component specifications

## 💼 Structured Finance Context

These rules are specifically designed for structured finance applications with considerations for:

- **User Types**: CLO managers, asset managers, deal modelers, investors, issuers
- **Regulatory Requirements**: SEC reporting, compliance, audit trails
- **Data Security**: Financial data protection and access controls
- **Professional Workflows**: Enterprise-grade interfaces and processes
- **Performance Requirements**: Real-time analytics and large dataset handling

## 🛠️ Customization

### **Rule Customization**
- Edit `.mdc` files to modify AI behavior
- Add new persona rules following the established naming pattern
- Customize templates in `.cursor/templates/`

### **Technology Adaptation**
- **UX Design**: Currently uses Material Design (ready for Moody's design system migration)
- **Technical Stack**: Supports React, Node.js/Python, Redis, desktop-first approach
- **Deployment**: Localhost development with cloud migration planning

### **Process Modification**
- **Requirements Process**: Structured theme → epic → story hierarchy
- **Design Process**: Atomic design methodology (atoms → molecules → organisms)
- **Development Process**: Phase-based planning with dependency management

## 📖 Documentation

### **Individual Rule Documentation**
Each rule file contains:
- **Activation Context**: When to use the persona
- **Methodology**: Systematic approach and best practices
- **Quality Standards**: Validation criteria and success metrics
- **Integration Points**: How the rule works with others

### **Template Usage**
- **Project Status**: Use for standardized project tracking
- **Lesson Learned**: Capture insights from troubleshooting and development

## 🔄 Workflow Integration

### **Complete Development Cycle**
```
Opportunity Analysis → Requirements Writing → UX Design → Technical Design
        ↓                    ↓               ↓              ↓
Project Management → Version Planning → Sprint Planning → Development
```

### **Cross-Rule Coordination**
- **Requirements** feed into **UX Design** and **Technical Design**
- **Technical Design** coordinates with **Project Management** for resource planning
- **Version Planning** aligns with **Sprint Planning** for execution
- **Troubleshooting** integrates with **Lessons Learned** for knowledge capture

## 📝 Contributing

### **Rule Development**
1. Follow the established naming pattern (`NN-persona-name.mdc`)
2. Include complete frontmatter with `description` and `alwaysApply` settings
3. Structure content with clear phase divisions and emoji markers
4. Test rule behavior with real project scenarios

### **Template Enhancement**
1. Maintain compatibility with existing project structures
2. Include comprehensive documentation and examples
3. Consider structured finance context and requirements
4. Validate template effectiveness through usage

## 📄 License

MIT License - See LICENSE file for details

## 🤝 Support

For questions about rule usage, customization, or integration:
1. Review individual rule documentation
2. Check template examples and usage patterns
3. Consult structured finance context considerations
4. Test rule behavior in development environment

---

**Ready to transform your Product Management workflow with AI-assisted development standards!** 🚀
