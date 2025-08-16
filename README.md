

---

# 🤖 Sci-Fi AI Personal Assistant

## 📌 Overview

This project implements a **voice-controlled AI personal assistant** built on **Raspberry Pi** for **home automation and interactive communication with humanoid robots**.

Inspired by sci-fi assistants like *Jarvis* from *Iron Man*, this system combines **Artificial Intelligence (AI)**, **Natural Language Processing (NLP)**, **Speech Recognition**, and **IoT** to create an affordable and efficient personal assistant.

The assistant can:

* 🎙️ Respond to **voice commands** with human-like interaction
* 💡 Control **home appliances** via NodeMCU + relay circuits
* 🌦️ Fetch and read out **date, time, weather, and internet search results**
* 🎶 Play music or YouTube videos
* 🗣️ Provide a **friendly, casual experience** rather than rigid fixed commands

---

## ⚡ Key Features

* **Voice Input & Output**

  * Speech-to-Text using **Google STT API**
  * Text-to-Speech feedback with **eSpeak TTS**
  * Dynamic, personalized replies

* **IoT Home Automation**

  * NodeMCU (ESP8266) with relays to control appliances
  * IP-based switching for lights, fans, motors, ACs, and heaters

* **AI & NLP Integration**

  * Understands natural language queries
  * Fetches real-time data (weather, date, time, search results)
  * Executes commands dynamically instead of fixed rules

* **Economical & Open Source**

  * Built with **low-cost hardware** (Raspberry Pi + NodeMCU)
  * Implemented in **Python scripts** with minimal configuration
  * Lightweight alternative to Jasper, Alexa, and Google Home

---

## 🖥️ System Architecture

The system is divided into **three main modules**:

1. **Speech-to-Text (STT) Module**

   * Converts voice input into text
   * Filters ambient noise for better recognition
   * Uses Google STT for high accuracy

2. **Command Module (Core Brain)**

   * Python script interprets commands and executes tasks
   * Interfaces with **NodeMCU (ESP8266)** to control appliances
   * Fetches weather, date, time, and performs Google/Wikipedia searches

3. **Text-to-Speech (TTS) Module**

   * Provides voice feedback using **eSpeak**
   * Responds casually with randomized sentences for natural interaction

---

## 📊 Results

* ✅ Controlled home appliances via simple **ON/OFF voice commands**
* ✅ Retrieved and read out **weather updates, date, time, and Google results**
* ✅ Played music and YouTube videos
* ✅ Delivered **interactive, friendly responses** for a human-like experience

---

## 🔮 Future Scope

* 📡 **Offline Speech Recognition** → Reduce internet dependency for rural areas
* 🌍 **Multi-language Support** → Add native language capability for accessibility
* 🧠 **Machine Learning Integration** → Allow the assistant to learn habits and adapt
* 🗂️ **Memory & Personalization** → Store preferences and recall them later
* 🔐 **Extended Modules** → Security, health tracking, scheduling, and more

---

This project demonstrates how **AI + IoT + NLP** can be combined to build a **sci-fi inspired personal assistant** that is **affordable, efficient, and interactive**.

---


