# CRM Import Readiness Checklist

Use this before rebuilding a lightweight CRM or operating system in Notion from CSV files.

## Before Import

- Confirm the core objects you need: companies, contacts, deals, tasks, projects, invoices, meetings, content, and metrics.
- Remove duplicate contacts and companies before import.
- Choose one owner field format and use it consistently across all CSV files.
- Normalize dates to `YYYY-MM-DD`.
- Keep a backup copy of every source CSV before importing.

## Pipeline Fields To Decide

- Deal stage names.
- Deal value currency.
- Expected close date.
- Lead source.
- Next action.
- Account owner.

## Workspace QA

- Open every imported database and check row counts against the source CSV files.
- Confirm company/contact/deal relations after import.
- Create filtered views for active deals, overdue tasks, upcoming meetings, and this month's revenue.
- Test the weekly review flow before relying on it operationally.

## Paid Kit

The paid Notion Business OS + CRM Kit is available at:

https://soloco-games.itch.io/notion-business-os-crm-kit/purchase

It is a CSV and Markdown rebuild/import kit. It is not a Notion duplicate link or an official Notion product.
