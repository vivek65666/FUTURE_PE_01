# Prompt Engineering Logic

## 1. Project Overview

This project demonstrates a structured prompt engineering workflow
for generating website copy for a local business.

The objective is to create reusable prompts that can generate:

- Homepage copy
- Service descriptions
- Call-to-action sections
- Tone-adapted website content

The prompts are designed to produce content that is clear,
business-specific, persuasive, and ready to publish on a website.

---

## 2. Business Context

### Business Name

UrbanGlow Salon

### Business Type

Unisex Salon

### Location

Bangalore, Karnataka

### Target Audience

- Young professionals
- Students
- Families
- Local residents

### Services

- Haircuts
- Hair Styling
- Hair Coloring
- Facial
- Manicure & Pedicure
- Bridal Packages

---

## 3. Problem Statement

Local businesses may have difficulty creating website content
that clearly communicates their services and encourages visitors
to take action.

The prompt system addresses the following problems:

- Unclear value proposition
- Generic website content
- Weak service descriptions
- Unclear calls-to-action
- Lack of tone consistency
- Lack of business-specific messaging

---

## 4. Prompt Engineering Strategy

The prompts follow a structured framework.

### Step 1 – Define the Role

The AI is assigned the role of an expert website copywriter.

This helps establish the expected writing expertise and output
quality.

### Step 2 – Provide Business Context

The prompt includes:

- Business name
- Business type
- Location
- Target audience
- Services

This reduces generic responses and makes the content relevant
to the selected business.

### Step 3 – Define the Objective

Each prompt clearly explains what needs to be generated.

For example:

- Homepage content
- Service descriptions
- CTA sections
- Tone adaptation

### Step 4 – Define Output Requirements

The prompt specifies the exact sections that should be generated.

For example, a service description includes:

1. Service name
2. Description
3. What's included
4. Customer benefit
5. CTA

### Step 5 – Define Tone

The prompts specify a tone appropriate for a local salon:

- Friendly
- Modern
- Professional
- Trustworthy
- Persuasive

### Step 6 – Add Local Context

The location is included so that the generated copy can naturally
reflect the local business context.

### Step 7 – Add SEO Guidance

Relevant local search terms are provided as guidance.

The prompt also instructs the AI to avoid keyword stuffing.

### Step 8 – Define Quality Constraints

The prompts instruct the AI to:

- Avoid generic AI language
- Avoid unnecessary jargon
- Focus on customer benefits
- Avoid unsupported claims
- Produce website-ready content

---

## 5. Prompt Components

The overall prompt framework can be represented as:

Role
+
Business Context
+
Target Audience
+
Services
+
Objective
+
Content Requirements
+
Tone
+
Local Context
+
SEO Guidance
+
Output Format

This structure makes the prompts reusable for similar local
business projects.

---

## 6. Prompt Modules

### Homepage Prompt

The homepage prompt generates:

- Hero headline
- Supporting subheadline
- Primary CTA
- Secondary CTA
- Business introduction
- Customer benefits
- Why choose us section

File:

`prompts/homepage_prompt.md`

---

### Services Prompt

The services prompt generates structured descriptions for each
business service.

Each service includes:

- Description
- What's included
- Customer benefit
- CTA

File:

`prompts/services_prompt.md`

---

### CTA Prompt

The CTA prompt generates action-oriented sections for:

- Appointment booking
- Contact
- Enquiry
- Visiting the salon

File:

`prompts/cta_prompt.md`

---

### Tone Adaptation Prompt

The tone adaptation prompt allows the same framework to be
adapted to different local business categories.

Supported categories include:

- Salon
- Cafe
- Clinic
- Coaching Institute
- Agency

File:

`prompts/tone_adaptation_prompt.md`

---

## 7. Reusability

The prompt framework is designed to be reusable.

To use it for another business, the following variables can be
changed:

- Business name
- Business type
- Location
- Target audience
- Services
- Tone

The core prompt structure can remain the same.

---

## 8. Output Quality Goals

The generated content is evaluated against the following criteria:

### Clarity

Visitors should quickly understand what the business offers.

### Relevance

The content should reflect the specific business and its
customers.

### Persuasiveness

The copy should communicate customer benefits and encourage
appropriate action.

### Consistency

The tone and messaging should remain consistent across the
website.

### Publishability

The final output should require minimal editing before being
used on a real website.

---

## 9. Tools Used

### ChatGPT

Used for prompt development, testing, refinement, and website
copy generation.

### GitHub

Used to document and organize the prompts and generated outputs
for evaluation.

### Markdown

Used to maintain structured project documentation.

---

## 10. Project Workflow

The workflow used in this project is:

1. Understand the business requirements
2. Define the target audience
3. Create structured prompts
4. Provide business context
5. Define output requirements
6. Generate website copy
7. Review the generated content
8. Apply quality constraints
9. Organize the final outputs
10. Document the prompt methodology

---

## 11. Expected Outcome

The final prompt system provides a repeatable approach for
generating website copy for local businesses.

The system can be adapted to different business types while
maintaining a consistent structure for:

- Homepage content
- Services content
- CTA content
- Tone adaptation

---

## 12. Key Learning

This project demonstrates that effective prompt engineering
requires more than asking an AI to "write website content."

A structured prompt provides:

- Clear context
- Defined objectives
- Specific constraints
- Appropriate tone
- Expected output structure
- Quality requirements

This helps produce more relevant and usable website content.
