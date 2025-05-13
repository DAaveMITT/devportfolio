# AI-Powered SEO Content Generator

This Python script uses OpenAI's GPT-4 API to dynamically generate localized SEO pages for towns using a template-based approach. It's designed for use cases like generating pages for "Bus Sales in [Town]" at scale.

## 🔧 How It Works

- Reads from an Excel file (`towns2.xlsx`) containing towns and keyword data
- Uses a TSX template with placeholders like `[[town_name]]`, `[[meta_title]]`, etc.
- Fills in the placeholders by calling GPT-4 with unique prompts for each section
- Outputs `.tsx` files optimized for local SEO

## 📁 Structure

