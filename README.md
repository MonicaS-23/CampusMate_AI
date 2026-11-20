
<div align="center">

  <h1>🎓 CampusMate AI</h1>

  <h3>Smart College Information and Student Support Assistant</h3>

  <p>
    An AI-powered college assistant that helps students access
    institutional information through an intelligent conversational interface.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" />
    <img src="https://img.shields.io/badge/Django-5.2-green?logo=django" />
    <img src="https://img.shields.io/badge/AI-RAG-purple" />
    <img src="https://img.shields.io/badge/Vector%20Database-FAISS-orange" />
    <img src="https://img.shields.io/badge/Status-Development-yellow" />
  </p>

</div>

<hr>

<h2>📌 About the Project</h2>

<p>
CampusMate AI is an intelligent college information and student support
platform developed to simplify access to institutional information.
It acts as a centralized digital assistant where students can ask
questions and receive relevant answers based on college documents
and academic information.
</p>

<p>
The system uses <b>Retrieval-Augmented Generation (RAG)</b> to retrieve
relevant information from an institutional knowledge base before
generating answers using an AI language model.
</p>

<p>
Instead of manually searching through multiple documents or contacting
administrative staff, students can interact with CampusMate AI and
get information through a simple chat interface.
</p>

<p><b>Institution:</b> Vivekanandha College of Engineering for Women (VCEW)</p>

<hr>

<h2>🎯 Project Objectives</h2>

<ul>
  <li>Provide instant access to college-related information.</li>
  <li>Reduce the time spent searching through institutional documents.</li>
  <li>Provide a centralized platform for student support.</li>
  <li>Reduce repetitive queries handled by administrative staff.</li>
  <li>Generate context-aware answers using college-specific data.</li>
  <li>Maintain an organized and searchable institutional knowledge base.</li>
</ul>

<hr>

<h2>👥 User Modules</h2>

<h3>1. Student Module</h3>

<ul>
  <li>Student registration and login.</li>
  <li>Personalized student dashboard.</li>
  <li>AI-powered conversational chat interface.</li>
  <li>Ask questions related to college information.</li>
  <li>Receive answers based on indexed institutional documents.</li>
  <li>Access available college information and knowledge resources.</li>
</ul>

<h3>2. Administrator Module</h3>

<ul>
  <li>Secure administrator login.</li>
  <li>Administrator dashboard.</li>
  <li>Upload institutional documents.</li>
  <li>Manage uploaded documents.</li>
  <li>View document indexing status.</li>
  <li>Re-index individual documents.</li>
  <li>Delete documents from the knowledge base.</li>
  <li>Rebuild the vector index.</li>
  <li>Manage the information available to the AI assistant.</li>
</ul>

<hr>

<h2>🤖 Key Features</h2>

<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>AI Chat Assistant</td>
    <td>Allows students to ask college-related questions using natural language.</td>
  </tr>
  <tr>
    <td>RAG Technology</td>
    <td>Retrieves relevant information from college documents before generating responses.</td>
  </tr>
  <tr>
    <td>Document Upload</td>
    <td>Administrators can upload PDF, DOCX and TXT files.</td>
  </tr>
  <tr>
    <td>Document Processing</td>
    <td>Extracts text and divides documents into smaller chunks for retrieval.</td>
  </tr>
  <tr>
    <td>Vector Search</td>
    <td>Uses FAISS to find relevant document chunks based on semantic similarity.</td>
  </tr>
  <tr>
    <td>AI Response Generation</td>
    <td>Uses an AI language model to generate answers using retrieved context.</td>
  </tr>
  <tr>
    <td>Knowledge Base Management</td>
    <td>Allows administrators to maintain and update institutional information.</td>
  </tr>
</table>

<hr>

<h2>📚 Information Available in the Knowledge Base</h2>

<p>The knowledge base is designed to contain institutional information such as:</p>

<ul>
  <li>College and department information</li>
  <li>Academic regulations</li>
  <li>Attendance policies</li>
  <li>Examination regulations</li>
  <li>Semester examination schedules</li>
  <li>Class timetables</li>
  <li>Placement eligibility and procedures</li>
  <li>Fee structure and scholarship details</li>
  <li>Student handbook and guidelines</li>
</ul>

<hr>

<h2>⚙️ How CampusMate AI Works</h2>

<p>The application follows a Retrieval-Augmented Generation (RAG) workflow.</p>

<h3>Document Processing Workflow</h3>

<ol>
  <li>Administrator uploads a college document.</li>
  <li>The system extracts text from the uploaded document.</li>
  <li>The extracted text is divided into smaller chunks.</li>
  <li>Each chunk is converted into a numerical embedding.</li>
  <li>The embeddings are stored in the FAISS vector store.</li>
  <li>The document becomes available for semantic retrieval.</li>
</ol>

<h3>Student Question and Answer Workflow</h3>

<ol>
  <li>Student enters a question in the chat interface.</li>
  <li>The question is converted into an embedding.</li>
  <li>FAISS searches for the most relevant document chunks.</li>
  <li>The retrieved information is provided as context to the AI model.</li>
  <li>The AI model generates a context-based response.</li>
  <li>The answer and available source information are returned to the student.</li>
</ol>

<div align="center">

  <h3>System Architecture</h3>

  <p><b>Administrator</b></p>
  <p>⬇</p>
  <p>Document Upload (PDF / DOCX / TXT)</p>
  <p>⬇</p>
  <p>Text Extraction and Chunking</p>
  <p>⬇</p>
  <p>Embedding Generation</p>
  <p>⬇</p>
  <p><b>FAISS Vector Database</b></p>

  <br>

  <p><b>Student</b></p>
  <p>⬇</p>
  <p>Ask a Question</p>
  <p>⬇</p>
  <p>Question Embedding</p>
  <p>⬇</p>
  <p>Semantic Retrieval from FAISS</p>
  <p>⬇</p>
  <p>Retrieved Context + AI Language Model</p>
  <p>⬇</p>
  <p><b>Context-Based Answer</b></p>

</div>

<hr>

<h2>🛠️ Technology Stack</h2>

<table>
  <tr>
    <th>Category</th>
    <th>Technology</th>
  </tr>
  <tr>
    <td>Programming Language</td>
    <td>Python</td>
  </tr>
  <tr>
    <td>Backend Framework</td>
    <td>Django</td>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>HTML, CSS, JavaScript</td>
  </tr>
  <tr>
    <td>Database</td>
    <td>SQLite</td>
  </tr>
  <tr>
    <td>AI Architecture</td>
    <td>Retrieval-Augmented Generation (RAG)</td>
  </tr>
  <tr>
    <td>Embedding Model</td>
    <td>Sentence Transformers - all-MiniLM-L6-v2</td>
  </tr>
  <tr>
    <td>Vector Database</td>
    <td>FAISS</td>
  </tr>
  <tr>
    <td>Language Model API</td>
    <td>Navigate Labs Nexus API - Nova Micro</td>
  </tr>
  <tr>
    <td>Document Processing</td>
    <td>PyPDF, Python-docx</td>
  </tr>
  <tr>
    <td>Development Environment</td>
    <td>Google Colab, Visual Studio Code</td>
  </tr>
</table>

<hr>

<h2>📂 Project Structure</h2>

<pre>
CampusMate-AI/
│
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
│
├── chatbot/
│   ├── models.py
│   ├── views.py
│   ├── services.py
│   └── urls.py
│
├── documents/
│   ├── models.py
│   ├── views.py
│   ├── services.py
│   ├── forms.py
│   ├── knowledge_base.py
│   └── samples.py
│
├── rag/
│   ├── loaders.py
│   ├── chunking.py
│   ├── embeddings.py
│   ├── vector_store.py
│   ├── service.py
│   └── datatypes.py
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── templates/
│   ├── accounts/
│   ├── admin_panel/
│   ├── dashboard/
│   └── landing.html
│
├── sample_documents/
│
├── media/
├── manage.py
├── requirements.txt
└── README.md
</pre>

<hr>

<h2>🚀 Installation and Setup</h2>

<h3>Prerequisites</h3>

<ul>
  <li>Python 3.10 or later</li>
  <li>pip package manager</li>
  <li>Navigate Labs Nexus API key</li>
</ul>

<h3>Step 1: Clone the Repository</h3>

<pre>
git clone YOUR_GITHUB_REPOSITORY_URL
cd CampusMate-AI
</pre>

<h3>Step 2: Create a Virtual Environment</h3>

<pre>
python -m venv venv
</pre>

<p>Activate the environment:</p>

<p><b>Windows:</b></p>

<pre>
venv\Scripts\activate
</pre>

<p><b>Linux / macOS:</b></p>

<pre>
source venv/bin/activate
</pre>

<h3>Step 3: Install Dependencies</h3>

<pre>
pip install -r requirements.txt
</pre>

<h3>Step 4: Configure Environment Variables</h3>

<p>Set the following environment variables using your own API credentials:</p>

<pre>
LLM_PROVIDER=openai
LLM_API_KEY=YOUR_NEXUS_API_KEY
LLM_BASE_URL=https://nexusapi.navigatelabs.ai
LLM_MODEL=nova-micro
LLM_API_STYLE=openai
LLM_CHAT_PATH=/v1/chat/completions
</pre>

<p>
<b>Important:</b> Never upload your actual API key, passwords,
database credentials or secret configuration files to GitHub.
</p>

<h3>Step 5: Apply Database Migrations</h3>

<pre>
python manage.py migrate
</pre>

<h3>Step 6: Create an Administrator Account</h3>

<pre>
python manage.py createsuperuser
</pre>

<h3>Step 7: Start the Development Server</h3>

<pre>
python manage.py runserver
</pre>

<p>Open the application in your browser:</p>

<pre>
http://127.0.0.1:8000/
</pre>

<hr>

<h2>🔒 Security and Data Handling</h2>

<ul>
  <li>Student and administrator authentication is managed through Django.</li>
  <li>Administrator-only document management pages require staff access.</li>
  <li>Uploaded documents are processed for knowledge-base indexing.</li>
  <li>API credentials should be maintained using environment variables or secure secrets.</li>
  <li>Production deployment requires appropriate host, HTTPS and security configuration.</li>
</ul>

<hr>

<h2>🌱 Future Enhancements</h2>

<ul>
  <li>Integration with live college ERP and student information systems.</li>
  <li>Real-time timetable and examination updates.</li>
  <li>Multilingual student interaction.</li>
  <li>Voice-based question and answer support.</li>
  <li>Advanced analytics for frequently asked questions.</li>
  <li>Improved document versioning and automatic knowledge-base synchronization.</li>
  <li>Cloud deployment for wider student accessibility.</li>
</ul>

<hr>

<h2>💡 Expected Impact</h2>

<p>
CampusMate AI aims to make college information more accessible,
reduce repetitive administrative queries and improve the student
experience through AI-powered institutional knowledge retrieval.
</p>

<hr>

<h2>👩‍💻 Project Information</h2>

<p><b>Project Name:</b> CampusMate AI</p>
<p><b>Project Type:</b> AI-powered Web Application</p>
<p><b>Domain:</b> Artificial Intelligence / Generative AI / Web Development</p>
<p><b>Core Concept:</b> Retrieval-Augmented Generation (RAG)</p>

<div align="center">
  <h3>🎓 CampusMate AI</h3>
  <p><i>Making College Information Smarter, Simpler and Accessible.</i></p>
</div>
