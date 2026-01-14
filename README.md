# QR Code–Based Railway Track Asset Tracking & AI Inspection System

A smart, end-to-end digital traceability and condition-monitoring system for Indian Railway track fittings using QR codes, cloud data, and AI-driven analytics.
The platform ensures lifecycle tracking, defect detection, predictive maintenance, and real-time engineering dashboards.

## Problem Statement

Indian Railway track components (sleepers, ERCs, fittings) lack:

End-to-end traceability

Real-time defect monitoring

Predictive maintenance intelligence

This leads to manual inspections, delayed fault detection, and safety risks.

## Solution Overview

This system assigns a unique QR + UID to every track fitting at manufacturing time and tracks it throughout its lifecycle using:

Mobile QR scanning

Cloud-based asset history

AI-driven defect detection

Predictive failure analytics

Digital twin visualization on map interfaces

## System Architecture (High Level)

Lifecycle Flow:

Component Manufactured

QR Code + UID Generated

QR + UID Engraved on Component

Inventory & Delivery Tracked

Installation at Track Site

QR Scanned → Auto Timestamp & Geo-Location

Asset Data Stored in Cloud Database

AI Analysis for Defects & Failure Prediction

Alerts Raised to Engineer Dashboard

Integration with UDM/TMS Portal

## 🏗️ System Architecture

The following diagram illustrates the **end-to-end architecture** of the QR Code–Based Railway Track Asset Tracking & AI Inspection System, covering the complete lifecycle from manufacturing to AI-driven predictive maintenance.

![System Architecture](docs/architecture.png)

##  Key Features
QR-Based Asset Traceability

Unique QR + UID per track fitting

Lifecycle tracking from manufacturing to maintenance

Auto Geo-Tagging

Exact latitude & longitude captured on every scan

Timestamp logged automatically

## Unified Engineer Dashboard

Mobile-friendly dashboard

Full asset history & defect records

Condition monitoring in real time

##  AI-Based Defect Detection

High-FPS camera data analyzed using AI

Detects cracks, misalignment, wear

Classifies defect severity

## Predictive Failure Analysis

AI models predict failure probability

Vendor comparison & quality scoring

Preventive maintenance insights

## Digital Twin Visualization

Track fittings mapped visually

Geo-linked asset representation

Easy fault localization

## Intelligent Alerts

If defect detected → alert raised instantly

Sent to engineer dashboard

Component (e.g., ERC) matched with sleeper index
