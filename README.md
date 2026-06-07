# incubyte-qa-assessment
Manual QA test cases (Traditional + BDD) for Gmail Compose functionality - Incubyte QA Assessment

# Gmail Compose Functionality - QA Test Cases

## Overview
This repository contains comprehensive manual test cases for Gmail's **Compose and Send** functionality, covering both Traditional and BDD (Behavior-Driven Development) formats.

## Files

| File | Format | Total Cases |
|------|--------|-------------|
| Gmail_Traditional_Test_Cases.xlsx | Traditional (Step-by-Step) | 40 (22 Positive + 18 Negative) |
| Gmail_BDD_Test_Cases.xlsx | BDD (Given/When/Then) | 25 (13 Positive + 12 Negative) |

## Features Covered
- Opening Compose window and verifying all UI elements
- Sending email with valid recipient, subject, and body
- Formatting Toolbar (Bold, Underline, Font change, Text color, Undo/Redo, Numbered list, Alignment)
- File Attachments (with 25MB size limit validation)
- Insert Hyperlink
- Insert Emoji
- Insert Photo (inline)
- Google Drive file insertion
- Confidential Mode (expiration and access restrictions)
- Email Signature
- More Options (Plain text mode, Spell check, Default to full screen, Label)
- Schedule Send (via dropdown next to Send button)
- Delete Draft (trash icon)
- Auto-save on accidental close
- CC/BCC functionality
- Network disconnection handling

## Test Approach
- **Positive cases**: Verify all features work as expected with valid inputs
- **Negative cases**: Validate error handling, boundary conditions, and edge cases
- Written from a real user's perspective — each case maps to an actual action performed on the Gmail UI

## Tools Used
- Manual testing
- Excel for test case documentation
- BDD format using Gherkin syntax (Given/When/Then)

## Author
Ganeshsatyasainukeswar
