# Sentiment Lab

You are building the production frontend for an academic major project called:

SENTIMENT ANALYSIS LAB

Project title:
“Sentiment Analysis Using Machine Learning and Large Language Models”

I have provided a complete Stitch-generated UI/design system for this project.

IMPORTANT:
The Stitch project is the SOURCE OF TRUTH for the visual design.

Do NOT redesign the application from scratch.

Do NOT replace the Stitch visual language with a generic Lovable/SaaS template.

Recreate and implement the Stitch UI faithfully while converting it into a maintainable, responsive, production-quality frontend.

==================================================

PROJECT PURPOSE
==================================================

This is a research-oriented sentiment analysis and model benchmarking platform.

The application compares:

TRADITIONAL MACHINE LEARNING

Naive Bayes

Logistic Regression

Support Vector Machine (SVM)

with:

TRANSFORMER-BASED MODELS

BERT

RoBERTa

The system supports:

Positive / Negative / Neutral sentiment classification

Dataset upload

Dataset preprocessing

Model training

Real-time sentiment prediction

Model comparison

Benchmarking

Confidence scores

Explainability

Analytics

Prediction history

Role-based access

Administrator management

The frontend must therefore feel like a serious ML research laboratory / analytics platform.

It must NOT feel like:

a chatbot

a marketing SaaS website

a generic admin dashboard

a cryptocurrency dashboard

a social media application

==================================================
2. STITCH DESIGN SYSTEM — FOLLOW EXACTLY

Use the provided Stitch DESIGN.md as the design-system source of truth.

Preserve the following design language.

BRAND PERSONALITY:

Sophisticated

Technical

Intelligent

Research-oriented

Enterprise-grade

Data-dense

Low-friction

VISUAL STYLE:

Modern corporate minimalist

Dark-mode-first

Deep-space navy/charcoal surfaces

Subtle borders

Tonal layering

Restrained glassmorphism only where already present

High information density

No excessive decoration

==================================================
3. EXACT COLOR SYSTEM

Implement the Stitch color tokens as reusable CSS variables/design tokens.

Primary background:
#0b1326

Lowest surface:
#060e20

Low surface:
#131b2e

Surface:
#171f33

High surface:
#222a3d

Highest surface:
#2d3449

Bright surface:
#31394d

Primary:
#c0c1ff

Primary container:
#8083ff

Secondary:
#4fdbc8

Secondary container:
#04b4a2

Main text:
#dae2fd

Secondary text:
#c7c4d7

Outline:
#908fa0

Outline variant:
#464554

Error:
#ffb4ab

Error container:
#93000a

Semantic sentiment colors:

POSITIVE:
Use emerald/green semantic treatment.

NEGATIVE:
Use rose/red semantic treatment.

NEUTRAL:
Use amber/yellow semantic treatment.

Important:
Do not randomly introduce additional brand colors.

Sentiment colors must remain semantically consistent throughout the application.

==================================================
4. TYPOGRAPHY

Use:

Inter

for:

headings

body text

navigation

buttons

cards

forms

Use:

JetBrains Mono

for:

confidence percentages

metrics

model metadata

technical labels

status tags

dataset statistics

table numeric values

IDs/version information

Preserve the Stitch typography hierarchy.

Display:
48px / 56px

Headline large:
32px / 40px

Headline medium:
24px / 32px

Headline small:
20px / 28px

Body large:
16px / 24px

Body:
14px / 20px

Technical label:
12px / 16px

Small metadata:
10px / 14px

Do not use oversized marketing typography inside the authenticated application.

==================================================
5. LAYOUT SYSTEM

Use the Stitch 8px spacing system.

Spacing:
4px
8px
16px
24px
32px
48px

Desktop:

240px fixed sidebar.

Main content:
12-column fluid grid.

Desktop content margin:
32px.

Mobile:
16px margins.

Tablet/mobile:
collapse the desktop grid appropriately.

Maintain the Stitch density.

Do not create excessive vertical whitespace.

==================================================
6. APPLICATION SHELL

Create ONE reusable authenticated application shell.

Components:

AppShell
Sidebar
Topbar
Breadcrumbs
PageHeader
UserMenu
NotificationButton

Sidebar navigation:

Dashboard
Analyze Text
Datasets
Preprocessing
Models
Model Comparison
Explainability
Analytics
Prediction History

Administrator section:

Administration

Bottom sidebar:

User profile
Role
Settings
Logout

The sidebar should support:

Expanded:
240px

Collapsed:
64px

Use Lucide icons or an equivalent clean outline icon set.

Do not use filled cartoon icons.

==================================================
7. ROUTING

Implement real frontend routes:

/
/login
/register

/dashboard
/analyze
/datasets
/datasets/:id
/preprocessing
/models
/models/:id
/train
/comparison
/explainability
/analytics
/history

/admin
/admin/users
/admin/datasets
/admin/models

/settings

Use route-level layouts correctly.

Protect authenticated routes.

For now use a simple mock authentication layer.

Do NOT connect a real authentication provider yet.

Keep authentication isolated so it can later be replaced with the real backend.

==================================================
8. LANDING PAGE

Reproduce the Stitch landing page.

Do not redesign it.

Purpose:

Introduce Sentiment Analysis Lab as a research platform.

Hero:

“Understand Sentiment. Compare Models. Trust the Results.”

Supporting content should communicate:

AI-powered sentiment analysis
Traditional ML benchmarking
Transformer-based contextual analysis
Explainable predictions

Primary CTA:
Open Analysis Dashboard

Secondary CTA:
Explore Methodology

Use the Stitch abstract AI/sentiment visualization.

Do not use stock photography.

Include a concise methodology flow:

Dataset
→ Preprocessing
→ Traditional ML / Transformer Models
→ Prediction
→ Evaluation
→ Visualization

==================================================
9. AUTHENTICATION

Implement the Stitch:

Sign In
and
Registration

screens.

Login:

Email
Password
Remember me
Forgot password
Sign In
Create Account

Registration:

Full Name
Email
Password
Confirm Password

Default registration role:
Analyst

Do not allow public users to register as Administrator.

Implement:

validation

loading state

error state

success state

==================================================
10. RESEARCH DASHBOARD

This is the primary application screen.

Reproduce the Stitch Research Dashboard faithfully.

Header:

Research Dashboard

Subtitle:
“Monitor sentiment predictions, model performance, and evaluation results.”

KPI cards:

Total Predictions
Positive
Neutral
Negative
Best Model Accuracy

Use mock research data initially.

Dashboard sections:

A. Sentiment Distribution

Donut/pie visualization.

B. Model Performance

Comparison of:

Naive Bayes
Logistic Regression
SVM
BERT
RoBERTa

Metrics:

Accuracy
Precision
Recall
F1-score

C. Sentiment Trend

Line chart.

D. Recent Predictions

Table containing:

Text
Model
Prediction
Confidence
Timestamp

Use realistic sample sentiment-analysis data.

==================================================
11. REAL-TIME ANALYSIS

Reproduce the Stitch Real-Time Analysis screen.

Title:

Analyze Text

Large text input.

Controls:

Model selector

Options:
Naive Bayes
Logistic Regression
SVM
BERT
RoBERTa
Compare All Models

Primary action:

Analyze Sentiment

Optional audio interface should remain available because the project implementation includes text and audio-based interaction.

Prediction result:

Sentiment
Confidence
Class probabilities
Model
Timestamp

Example:

Text:
“The product quality exceeded my expectations.”

Prediction:
Positive

Confidence:
96.4%

Probability:

Positive 96.4%
Neutral 2.1%
Negative 1.5%

IMPORTANT:

For the current frontend, clicking Analyze Sentiment should use mock inference.

Do NOT pretend a real ML model is running.

Clearly isolate this mock service from the UI.

==================================================
12. MODEL COMPARISON

Reproduce the Stitch Model Benchmarking screen.

Create a research benchmark interface.

Comparison table:

Model
Model Type
Accuracy
Precision
Recall
F1-score
Inference Time

Models:

Naive Bayes
Traditional ML

Logistic Regression
Traditional ML

SVM
Traditional ML

BERT
Transformer

RoBERTa
Transformer

Charts:

Grouped metric comparison.

Accuracy
Precision
Recall
F1-score

Add:

Dataset selector
Model type filter
Metric filter

Export Benchmark Report button.

Export can initially create a frontend placeholder action.

==================================================
13. DATASET MANAGEMENT

Reproduce the Stitch Dataset Management screen.

Dataset upload:

CSV
JSON

Upload interface:

Drag and drop
Browse files

Dataset table:

Dataset Name
Records
Labels
Status
Last Updated
Actions

Example datasets:

IMDb Movie Reviews
Amazon Reviews
SST-2

Dataset detail screen:

Total records
Positive samples
Negative samples
Neutral samples
Missing values
Duplicate records
Average text length

Processing status:

Uploaded
→ Cleaned
→ Tokenized
→ Vectorized
→ Ready

Use mock data.

File upload should work on the frontend.

Do not send files to a nonexistent backend.

Store the uploaded file temporarily in frontend state and display realistic processing states.

==================================================
14. PREPROCESSING

Reproduce the Stitch Data Preprocessing Pipeline.

Visual pipeline:

Raw Dataset
↓
Text Cleaning
↓
Normalization
↓
Tokenization
↓
Stop-word Handling
↓
TF-IDF Vectorization / Transformer Tokenization
↓
Processed Dataset

Controls:

Lowercase
Remove punctuation
Remove stop words
Normalize whitespace
Tokenization
Handle missing values

Before/after preview.

Button:

Run Preprocessing

Implement frontend simulation:

Idle
→ Processing
→ Completed

Do not claim actual preprocessing is happening until the Python backend is connected.

==================================================
15. MODEL LIBRARY

Reproduce the Stitch Model Library.

Cards:

Naive Bayes
Logistic Regression
SVM
BERT
RoBERTa

Each model should show:

Model type
Status
Accuracy
F1-score
Dataset
Version
Last trained

Actions:

Evaluate
Run Prediction
View Details

Use reusable ModelCard component.

==================================================
16. MODEL TRAINING

Reproduce the Stitch Model Training Configuration screen.

Sections:

Dataset
Model
Preprocessing
Training Configuration
Evaluation

Traditional ML controls:

TF-IDF
N-gram range
Maximum features
Train/test split

Transformer controls:

Model
Maximum sequence length
Batch size
Epochs
Learning rate

Use progressive disclosure for advanced settings.

Primary button:

Start Training

After clicking:

Training progress
Validation loss
Accuracy
Precision
Recall
F1-score

For frontend phase:
simulate training using mock progress data.

Do NOT fake a completed real-world training job.

Clearly structure the code so this can later call:

POST /api/training/start

and poll:

GET /api/training/:id

==================================================
17. EXPLAINABILITY

This is one of the most important research screens.

Reproduce the Stitch Prediction Explainability design.

Show:

Original text

Predicted sentiment

Confidence

Model

Explanation method

Highlight influential tokens.

Example:

“The camera quality is excellent, but the battery life is disappointing.”

Positive influence:
excellent

Negative influence:
disappointing

Context:
but
battery life

Explanation methods:

SHAP
Attention

Create a visually strong token-importance visualization.

Implement mock explanation data now.

Structure it so later it can consume real SHAP/attention results from the Python backend.

==================================================
18. ADVANCED ANALYTICS

Reproduce the Stitch Advanced Analytics screen.

Charts:

Sentiment distribution
Sentiment trend
Model performance
Confusion matrix
Precision by class
Recall by class
F1-score by class

Filters:

Date range
Dataset
Model

Date presets:

7 days
30 days
90 days
Custom

Add:

Export Analytics

Use reusable chart components.

Charts must have:

clear axes

legends

tooltips

empty states

loading states

==================================================
19. PREDICTION HISTORY

Reproduce the Stitch Prediction History screen.

Columns:

Timestamp
Input Text
Model
Prediction
Confidence
Dataset
Actions

Filters:

Model
Sentiment
Date
Confidence

Search input.

Clicking a prediction should open a detail drawer/modal.

Detail:

Original text
Prediction
Confidence
Class probabilities
Model
Explanation

==================================================
20. ADMINISTRATION

Create an administrator interface consistent with Stitch.

Dashboard:

Total Users
Active Analysts
Datasets
Trained Models
Predictions

User management table:

Name
Email
Role
Status
Last Active
Actions

Roles:

Analyst
Administrator

Create role-based navigation.

Analysts must not see administrator functionality.

==================================================
21. SETTINGS

Create settings using the same design language.

Tabs:

Profile
Security
Appearance
Model Preferences
Notifications

Keep settings clean and compact.

==================================================
22. MOCK API ARCHITECTURE

VERY IMPORTANT:

Do not tightly couple mock data to React components.

Create a service layer.

For example:

services/
analysisService
datasetService
modelService
trainingService
analyticsService
historyService
authService

Functions:

analyzeText()
compareModels()
getDatasets()
getDataset()
uploadDataset()
preprocessDataset()
getModels()
getModel()
startTraining()
getTrainingStatus()
getModelComparison()
getAnalytics()
getPredictionHistory()
getPrediction()
getExplanation()
login()
register()

Initially these return mock data.

The UI must not need to be rewritten when these services are replaced by real REST API calls.

==================================================
23. FUTURE BACKEND CONTRACT

Design the frontend service layer around a future Python backend.

Potential endpoints:

POST /api/auth/login

POST /api/auth/register

POST /api/analyze

POST /api/analyze/compare

GET /api/models

GET /api/models/:id

GET /api/datasets

POST /api/datasets/upload

POST /api/datasets/:id/preprocess

POST /api/training/start

GET /api/training/:id

GET /api/comparison

GET /api/analytics

GET /api/predictions

GET /api/predictions/:id

GET /api/predictions/:id/explanation

Do not implement these endpoints now.

Create clean interfaces/types for them.

==================================================
24. TYPESCRIPT DATA MODELS

Create reusable TypeScript interfaces/types:

Sentiment =
'positive' | 'negative' | 'neutral'

ModelType =
'traditional_ml' | 'transformer'

ModelName =
'naive_bayes'
| 'logistic_regression'
| 'svm'
| 'bert'
| 'roberta'

Prediction

ModelMetrics

Dataset

TrainingJob

Explanation

AnalyticsData

User

==================================================
25. COMPONENT ARCHITECTURE

Build reusable components.

Examples:

AppShell
Sidebar
Topbar
PageHeader

MetricCard
StatusBadge
SentimentBadge
ModelBadge

DataTable
SearchInput
FilterBar

PredictionCard
PredictionResult
ConfidenceMeter

ModelCard
ModelPerformanceTable
ComparisonChart

DatasetCard
DatasetUpload
DatasetStatus

PreprocessingPipeline

TrainingProgress
TrainingMetrics

ExplainabilityText
TokenImportance
ExplanationPanel

ConfusionMatrix
AnalyticsChart

Modal
Drawer
Tooltip
Toast

EmptyState
LoadingState
ErrorState

Do not duplicate components between pages.

==================================================
26. INTERACTION QUALITY

Every major interaction must have proper states.

Buttons:

Default
Hover
Pressed
Disabled
Loading
Success

Inputs:

Default
Focus
Filled
Error
Disabled

Upload:

Idle
Uploading
Processing
Completed
Failed

Prediction:

Idle
Analyzing
Result
Error

Training:

Idle
Queued
Running
Completed
Failed

Charts:

Loading
Loaded
Empty
Error

Tables:

Loading
Loaded
Empty
Error

Use tasteful transitions.

No excessive animation.

==================================================
27. RESPONSIVE BEHAVIOR

Desktop:
240px sidebar.

Tablet:
collapsible sidebar.

Mobile:
navigation drawer or bottom navigation.

12-column desktop layout should collapse cleanly.

Tables:
horizontal scroll or responsive cards.

Charts:
responsive width.

Forms:
single-column on mobile.

Never allow horizontal page overflow.

==================================================
28. ACCESSIBILITY

Implement:

Keyboard navigation
Visible focus states
ARIA labels where necessary
Semantic buttons
Accessible form labels
Readable contrast
Tooltips for icon-only actions

Do not rely on color alone for sentiment status.

For example:

Positive

icon + label + semantic color

Negative

icon + label + semantic color

Neutral

icon + label + semantic color

==================================================
29. PERFORMANCE

Keep the frontend lightweight.

Avoid unnecessary dependencies.

Lazy-load heavy analytics screens where appropriate.

Avoid rerendering large tables unnecessarily.

Use reusable chart components.

Keep mock datasets separated from components.

==================================================
30. DATA VISUALIZATION

The charts are part of the research interface.

Do not make them decorative.

Every chart must communicate a measurable research result.

Use:

clear axis labels

readable legends

meaningful tooltips

consistent metric formatting

consistent semantic colors

accessible contrast

Do not distort chart scales.

Do not use 3D charts.

Do not use pie charts where a bar chart would communicate model comparison better.

==================================================
31. IMPORTANT RESEARCH TERMINOLOGY

Use technically accurate terminology.

Prefer:

“Traditional Machine Learning”

and:

“Transformer-based Model”

instead of calling every transformer model an “LLM”.

Use:

BERT
RoBERTa
Naive Bayes
Logistic Regression
SVM

Use:

Accuracy
Precision
Recall
F1-score

Use:

Confidence
Class Probability
Inference Time
Training Time
Confusion Matrix
Explainability
SHAP
Attention

==================================================
32. REALISTIC SAMPLE DATA

Use realistic research data.

Do not use:
“Lorem ipsum”
“Test model”
“Sample text”
“John Doe”

Use examples related to:

product reviews

movie reviews

social comments

customer feedback

Example:

“The product quality exceeded my expectations.”

Positive
96.4%
BERT

Example:

“The camera is excellent, but the battery life is disappointing.”

Use appropriate mixed/neutral sample classification and realistic confidence.

==================================================
33. IMPORTANT — DO NOT FAKE ML RESULTS

The frontend may use mock values for demonstration.

But the UI architecture must clearly separate:

MOCK DATA

from:

REAL MODEL OUTPUT

Never create a fake loading animation that implies a real ML model executed if it did not.

Use comments/documentation explaining where backend responses will eventually replace mock services.

==================================================
34. VISUAL FIDELITY REQUIREMENT

The provided Stitch ZIP contains the intended screens and DESIGN.md.

Treat them as design references.

Preserve:

page hierarchy

navigation

spacing

colors

typography

cards

tables

charts

icon style

border treatment

density

dark theme

component proportions

If the Stitch implementation contains a component that can be directly translated into React/Tailwind, reproduce its visual behavior rather than inventing a different component.

Do not simplify the UI into generic cards.

==================================================
35. FINAL QUALITY BAR

The final frontend should look like:

A professional research-grade ML experimentation platform.

It should be credible enough to demonstrate to:

project guide

internal examiner

external examiner

technical interviewer

research panel

It should feel like a real product, not a student template.

Before finishing, verify:

all routes work

sidebar navigation works

buttons have meaningful interactions

forms validate

mock services work

charts render

tables render

filters work

prediction detail opens

explanation screen works

responsive layouts work

no broken links

no console errors

no placeholder Lorem Ipsum

no unnecessary pages

no generic SaaS redesign

no visual inconsistency between screens

Build the frontend incrementally and keep the existing Stitch design system intact.

Start with the application shell and core routes, then implement the screens using reusable components and mock services.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/8703ebda-8046-485b-abca-c96c27d50f05).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
