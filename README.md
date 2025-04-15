# AI Travel Planner 🌎✈️

An intelligent travel planning assistant that helps users plan their trips by finding flights, hotels, restaurants, and providing local insights.

## Features

### 🔍 Smart Travel Search
- Single-input natural language processing for travel details
- Intelligent parsing of dates, locations, and preferences
- Real-time flight and hotel search
- Progress tracking for search operations

### 🤖 AI-Powered Assistants
- **Travel Assistant**: Helps with trip planning and itinerary details
- **Research Assistant**: Provides local insights and restaurant recommendations
- Restaurant database with vector search capabilities (only enabled for Thailand currently)
- Integration with search engines for up-to-date information

### 🏨 Comprehensive Results
- Flight options and pricing
- Hotel recommendations
- Local restaurant suggestions with detailed information:
  - Ratings and reviews
  - Opening hours
  - Location and contact details
  - Price ranges
  - Available services

### 💬 Interactive Chat Interface
- Natural conversation with AI assistants
- Suggested prompts for easy starting points
- Context-aware responses based on your travel plans
- Rich formatting for clear information display

## Technical Stack

- **Frontend**: Streamlit
- **Language Models**: Ollama/Claude
- **Vector Store**: ChromaDB
- **Embeddings**: nomic-embed-text
- **Search**: DuckDuckGo API
- **Data Storage**: JSON + Vector Database
- **Web Data (Realtime, Datasets, Scraping)**: BrightData

## Getting Started

1. **Install Dependencies**
```bash
pip install -r requirements.txt
```

2. **Environment Setup**
```bash
# Create a .env file with necessary API keys and configurations
cp sample.env .env
```

3. **Initialize the Application**
```bash
cd frontend
streamlit run frontend.py
```

4. **Run the Backend**
```bash
cd backend
python app.py
```

## Usage

1. **Enter Travel Details**
   - Use natural language to describe your trip
   - Example: "I want to travel to Bangkok from New York from July 1st to July 10th"

2. **View Results**
   - Check flight options and pricing
   - Browse hotel recommendations
   - Explore local restaurants

3. **Get Local Insights**
   - Chat with the Research Assistant about local attractions
   - Get restaurant recommendations
   - Learn about local customs and travel tips

