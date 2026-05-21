# EAC System — AI-Enabled CapEx/OpEx Classification

## What This Does
Automatically classifies engineer work activities as **CapEx** or **OpEx** using a 5-rule weighted AI engine. Built for the Infovision technical assessment.

## How to Run (No Install Needed!)
1. Download `EAC_System_Standalone.html`
2. Double-click to open in any browser (Chrome, Edge, Firefox)
3. Data loads automatically — no server needed

## Live App
> Vercel URL: https://eac-system-topaz.vercel.app

## Files in This Repo
| File | What it is |
|------|-----------|
| `EAC_System_Standalone.html` | Complete working application |
| `EAC_Architecture_Document.docx` | Full system architecture document |
| `EAC_Form_Records_10Rows_Classified.xlsx` | 10 form records extracted + classified |

## Features
- ✅ Excel file upload (drag & drop EAC_Dataset.xlsx)
- ✅ 10 survey forms pre-parsed and classified
- ✅ CapEx/OpEx classification engine (5 rules, confidence scores)
- ✅ Capitalisation shift metric dashboard
- ✅ Manual override capability
- ✅ Audit trail view
- ✅ Coming Soon connector panel (Google Drive, BigQuery, Sheets, Jira, Slack)
- ✅ 6-stage pipeline visualisation

## Classification Engine Rules
| Rule | Weight | Signal |
|------|--------|--------|
| R1 | 35% | CapEx Eligible % |
| R2 | 20% | VZZ Cost Class |
| R3 | 20% | Activity Type |
| R4 | 15% | Labor Survey Category |
| R5 | 10% | Milestones Completed |

## Submitted By
Name: Charan Yelubandi
Email: ram.newcareer@gmail.com
Date: May 21, 2026
