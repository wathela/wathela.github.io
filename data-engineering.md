---
layout: default
title: "AI and Data Engineering"
permalink: /data-engineering/
---


<div id="data-engineering" class="tab-content"> 
    <h2>AI and Data Engineering Projects</h2>

    <!-- WarChat: AI-Powered Conflict Monitoring -->
    <div id="warchat">
        <h3>WarChat</h3>
        <h4>AI-Powered Conflict Monitoring for Sudan</h4>
        <p>WarChat is an AI-driven web application designed to track and analyze the ongoing war in Sudan. It integrates advanced technologies to provide real-time insights and intelligent retrieval of conflict-related information.</p>

        <h4>Tech Stack:</h4>
        <ul>
            <li><strong>DeepSeek Distilled R1:</strong> Primary AI model for chat-based analysis</li>
            <li><strong>Ollama:</strong> Runs DeepSeek locally for efficient processing</li>
            <li><strong>Knowledge Base RAG:</strong> Context-aware retrieval system</li>
            <li><strong>Nomic-Embed-Text:</strong> For data embedding for semantic search</li>
            <li><strong>pgvector:</strong> Vector database for embedding storage</li>
            <li><strong>Cosine Similarity:</strong> For matching user prompt with stored embedding</li>
        </ul>

        <h4>Infrastructure & Deployment:</h4>
        <ul>
            <li><strong>FastAPI:</strong> Backend API endpoints</li>
            <li><strong>Streamlit:</strong> APP frontend</li>
            <li><strong>Airflow & Spark:</strong> For ACLED data orchestration and automated daily updates</li>
        </ul>

        <h4>System Flowchart:</h4>
        <p align="center">
            src="<img src="https://github.com/wathela/wathela.github.io/blob/main/assets/images/warchat_images/warchart_flowchart_wb.png" width="600px">
        </p>

        <h4>Screenshots:</h4>
        <p align="center">
            <img src="assets/warchat_images/app_screen1.png" width="600px">
        </p>
        <p align="center">
            <img src="assets/warchat_images/app_screen2.png" width="600px">
        </p>
        <h4>Full source code Available on <a href="https://github.com/wathela/WarChat">GitHub</a>.</h4>
     
    </div>


    <!-- End-to-End Data Engineering Project -->
    <div id="end-to-end-data-engineering-project">
        <h3>End-to-End Data Engineering Project</h3>
        <h4>Description:</h4>
        <p>This project demonstrates how to implement an end-to-end data engineering pipeline using tools from the modern data stack, including <strong>AirByte</strong>, <strong>DBT</strong>, and <strong>Dagster</strong>.</p>
        <h4>Key Learnings:</h4>
        <ul>
            <li><strong>Data Modeling:</strong> Best practices for organizing data into logical structures.</li>
            <li><strong>Testing & Documentation:</strong> Techniques for ensuring data quality and maintaining proper documentation.</li>
            <li><strong>Version Control:</strong> Managing changes to data pipelines with proper version control methods.</li>
            <li><strong>Extract, Load, Transform (ELT):</strong> Efficient methods to extract, load, and transform data into a unified, analytics-ready format.</li>
        </ul>
        <h4>Tools Used:</h4>
        <ul>
            <li><strong>AirByte:</strong> For extracting and loading data.</li>
            <li><strong>DBT:</strong> For transforming data into a structured and analytics-ready state.</li>
            <li><strong>Dagster:</strong> For orchestrating and managing the end-to-end pipeline.</li>
        </ul>
        <h4>Full Implementation Available on <a href="https://github.com/wathela/AirByte-DBT-Dagster-Project">GitHub</a>.</h4>
    </div>
</div>