# Setup Guide

This guide explains how to set up the Generative AI Roadmap Scheduler in Google Sheets.

## 1. Import Roadmap

- Open [Google Sheets](https://sheets.google.com/)
- File → Import → Upload → choose `GenerativeAI_Roadmap_Final_With_Links_GoogleSheets.csv`

## 2. Add Apps Script

- Extensions → Apps Script
- Copy-paste code from `apps-script/scheduler.gs`
- Save and run `onOpen()` → grant permissions

## 3. Sync with Calendar

- In Google Sheets → Menu **GenAI Scheduler → Sync All to Calendar**
- Events will be created in your Google Calendar
