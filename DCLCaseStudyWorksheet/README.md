# CaseStudyWorksheet README

## Overview
CaseStudyWorksheet is a leadership analysis tool that generates structured worksheets from case study documents. It analyzes leadership scenarios and creates 8-column analytical frameworks for educational and professional development purposes.

## Getting Started

### Initial Setup
1. Start a new conversation with the CaseStudyWorksheet tool
2. The tool will display a welcome message and available commands
3. Begin by uploading your first document

### Basic Workflow
1. **Upload** - Add your case study document
2. **Generate** - Create worksheet in your preferred format
3. **Analyze** - Use the structured output for leadership development

## Commands

### Document Management
- `/upload` - Add a new case study document for analysis
- `/list` - View all uploaded documents with their IDs and titles

### Worksheet Generation
- `/markdown [title or ID]` - **Recommended** - Generate markdown table (most portable)
- `/text [title or ID]` - Generate plain text table for copy-paste
- `/pdf [title or ID]` - Generate downloadable PDF worksheet
- `/latex [title or ID]` - Generate LaTeX code (requires Overleaf account at https://www.overleaf.com)

### Help
- `/help` - Display all available commands

## Worksheet Structure

Each generated worksheet contains 8 analytical columns:

| Column | Description |
|--------|-------------|
| **Key Players** | Up to 4 influential individuals or groups |
| **Interests** | Needs, wants, desires, concerns, and fears |
| **Facts** | Verifiable truths that impact decision-making |
| **Assumptions** | Beliefs assumed true due to lack of facts |
| **Paradigms** | Widely accepted models or conventional wisdom |
| **End State** | Desired future conditions for objectives |
| **Problem** | Obstacles preventing achievement of end state |
| **Vision** | Value-driven image inspiring behavior and change |

## Usage Guidelines

### Document Requirements
- Text-based case studies or leadership scenarios
- Articles containing clear situational context
- Documents with identifiable stakeholders and challenges

### Analysis Constraints
- Maximum 4 key players per document
- All analysis based strictly on provided text
- Unknown values marked as "Unknown" rather than fabricated

### Output Recommendations
- **Markdown format** is recommended for maximum portability
- Use **text format** for simple note-taking applications
- Use **PDF format** for formal presentations or printing
- Use **LaTeX format** for academic or publication purposes

## Example Usage

```
/upload
[Upload your case study document]

/list
Document ID: DOC001
Title: Leadership Crisis at Company X

/markdown DOC001
[Generates structured leadership analysis worksheet]
```

## Troubleshooting

### Common Issues
- **Document not uploading**: Ensure document is text-based and readable
- **Incomplete analysis**: Verify document contains sufficient detail about stakeholders and situations
- **LaTeX rendering**: Use https://www.overleaf.com to compile LaTeX output

### Best Practices
- Upload documents with clear leadership scenarios
- Use descriptive titles for easy identification
- Generate worksheets in multiple formats for different use cases

## Support
For technical issues or questions, refer to the `/help` command within the tool.