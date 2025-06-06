# Leaked System Prompts Collection

[![Repository Size](https://img.shields.io/github/repo-size/JoshKCIT/ai_system_prompts_leaked_main)](https://github.com/JoshKCIT/ai_system_prompts_leaked_main)JoshKCIT/ai_system_prompts_leaked_main/main)](https://github.com/JoshKCIT/ai_system_prompts_leaked_main/commits/main)
[![License](https://img.shields.io/badge/license-Research-purple.svg)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/JoshKCIT/ai_system_prompts_leaked_main)](https://github.com/JoshKCIT/ai_system_prompts_leaked_main/graphs/contributors)
[![Stars](https://img.shields.io/github/stars/JoshKCIT/ai_system_prompts_leaked_main)](https://github.com/JoshKCIT/ai_system_prompts_leaked_main/stargazers)

> ⚠️ **Important Notice**: All prompts in this repository are sourced from various public locations, leaks, and reverse engineering efforts. This repository serves as an archive and research resource. Use responsibly and in accordance with applicable laws and terms of service.

## 📚 Overview

This repository maintains a comprehensive collection of system prompts from various LLM-based services. It serves as a reference for researchers, developers, and AI enthusiasts interested in understanding how different AI systems are prompted and configured.

### 🔍 Quick Links
- [Repository Structure](#-repository-structure)
- [Contributing Guidelines](#-contributing-guidelines)
- [Technical Details](#-technical-details)
- [Legal Considerations](#-legal-and-ethical-considerations)
- [Maintenance](#-maintenance)
- [Related Resources](#-related-resources)

## 📁 Repository Structure

```
.
├── Anthropic/       # Claude and related system prompts
├── OpenAI/          # GPT models and related prompts
├── Perplexity/      # Perplexity AI prompts
├── X.ai/            # Grok and related prompts
├── Other-AIs/       # Various other AI systems
├── Codeium/         # Codeium-specific prompts
├── Cursor/          # Cursor IDE prompts
├── Notion/          # Notion AI prompts
├── Meta/            # Meta AI prompts
├── GitHub/          # GitHub Copilot prompts
├── Discord/         # Discord AI prompts
├── Microsoft/       # Microsoft AI prompts
├── Google/          # Google AI prompts
└── Legacy/          # Historical prompts
```

### File Naming and Organization Rules

1. **File Naming Convention**
   - Format: `service-name_version_date.md`
   - Example: `anthropic-claude-3.5-sonnet_20240306.md`
   - Use lowercase with hyphens for service names
   - Use underscores to separate version and date
   - Use YYYYMMDD format for dates
   - No future dates allowed
   - No special characters except hyphens and underscores

2. **File Organization**
   - Each service should have its own directory
   - All files must be in their correct service directory
   - No files should be in the root directory except README.md
   - Use consistent casing (lowercase) for all filenames
   - Group related files in subdirectories if needed

3. **File Content Requirements**
   - Must include source attribution in header
   - Must include version information
   - Must include date of collection
   - Must include any relevant metadata
   - Must follow the established format for the file type

## 🤝 Contributing Guidelines

### Submitting New Prompts

1. **Format Requirements**
   - Match the existing document format
   - Include verifiable sources or reproducible prompts
   - Follow the established naming convention: `service-name_version_date.md`
   - Include source attribution in the file header
   - Add relevant metadata (version, date, source)

2. **Submission Methods**
   - **Preferred**: Submit a PR with complete documentation
   - **Alternative**: Open an Issue with a link to verifiable sources
   - Include test cases or examples where applicable

3. **Important Notes**
   - This repository is cited in academic papers
   - Do not include sensitive commercial source code
   - Respect DMCA guidelines to prevent repository takedown
   - Always include source attribution
   - Verify prompt authenticity before submission

## 🔧 Technical Details

### Character Encoding
System messages may contain various escaped characters:
```json
{
  "newline": "\\n",
  "tab": "\\t",
  "quotes": {
    "single": "\\u2019",
    "double": ["\\u201c", "\\u201d"]
  },
  "space": "\\u00a0"
}
```

### File Types and Formats
The repository includes various file formats:
- Markdown (`.md`) - Primary documentation format
- Text (`.txt`) - Raw prompt files
- JSON - Structured prompt data
- XML - Configuration files
- JavaScript (`.js`) - Implementation examples

### Content Categories

1. **System Prompts**
   - Core system instructions
   - Behavioral guidelines
   - Safety protocols
   - Role definitions
   - Context management

2. **Tool Integration**
   - API specifications
   - Function definitions
   - Integration guidelines
   - Authentication methods
   - Rate limiting rules

3. **Documentation**
   - Usage examples
   - Best practices
   - Implementation notes
   - Version history
   - Compatibility information

## ⚖️ Legal and Ethical Considerations

- Respect intellectual property rights
- Do not include proprietary code
- Follow responsible disclosure practices
- Maintain academic integrity
- All prompts are sourced from public locations or leaks
- Use for research and educational purposes only
- Comply with applicable laws and regulations
- Respect terms of service of original services

## 🔄 Maintenance

- Regular updates to reflect new versions
- Verification of prompt authenticity
- Documentation of changes
- Removal of outdated content
- Source attribution tracking
- Quality assurance checks
- Community feedback integration

## 📝 License

This repository is for educational and research purposes only. Use responsibly and in accordance with applicable laws and regulations.

## 🔗 Related Resources

- [AI Safety Resources](https://github.com/topics/ai-safety)
- [LLM Research Papers](https://github.com/topics/llm-research)
- [AI Ethics Guidelines](https://github.com/topics/ai-ethics)
- [Prompt Engineering Resources](https://github.com/topics/prompt-engineering)
- [AI Development Tools](https://github.com/topics/ai-development)

---

<div align="center">
  <sub>Built with ❤️ for the AI research community</sub>
  <br>
  <sub>Last updated: June 2025</sub>
</div>
