# World-Model-for-Indian-Cities
A World Model for Urban Traffic Percolation: AI-Based Prediction Under Network and Traffic Constraints

# World Model for Indian Cities

## An AI-Driven Approach to Understanding Urban Traffic Systems

## Overview

This project explores the idea of building a World Model for Indian cities, starting with urban traffic in Delhi. The main objective is to understand how traffic conditions evolve across a road network and explore how data-driven models can help analyze congestion and improve traffic signal management.

Instead of looking at traffic as an isolated problem at individual intersections, I am exploring how roads, intersections, vehicle movement, and traffic signals can be represented as parts of a connected and dynamic system.

This is an ongoing research project developed as part of my IP (Independent Project).

## Problem Statement

Urban traffic congestion is influenced by several interconnected factors, including vehicle flow, queue formation, road connectivity, and traffic signal timings.

Traditional approaches that focus only on identifying whether a road is congested provide limited insight into how congestion develops and how interventions might affect surrounding roads.

The goal of this project is to explore a data-driven framework that can represent traffic conditions, analyze the road network, and evaluate possible traffic management strategies.

## Objectives

- Develop a structured representation of urban road networks using graph-based modelling.
- Explore methods to quantify traffic conditions using numerical congestion values.
- Analyze traffic flow, throughput, and queue lengths at selected intersections.
- Experiment with adaptive traffic signal green-time allocation based on observed traffic conditions.
- Simulate and compare adaptive signal timings with fixed-time approaches.
- Establish a foundation for developing more advanced predictive models of urban traffic systems.

## Approach and Methodology

### 1. Traffic Data Analysis

I explore traffic observations to understand congestion patterns, vehicle movement, and queue formation at selected intersections in Delhi.

### 2. Road Network Representation

The road network is represented as a graph, where nodes represent locations or intersections and edges represent connections between them. This provides a structured way to analyze relationships between different parts of the network.

### 3. Congestion Modelling

Traffic conditions are translated into numerical representations to explore how congestion can be quantified and incorporated into a mathematical model.

### 4. Queue Length and Traffic Flow Analysis

I investigate queue lengths and vehicle throughput to understand traffic conditions at individual approaches and evaluate how queues may change under different traffic management strategies.

### 5. Adaptive Signal Timing

I experiment with allocating green time according to traffic conditions and lane-level demand. The objective is to explore whether adaptive allocation can reduce queues compared with a fixed-time baseline.

### 6. Simulation and Evaluation

The proposed signal-timing strategies are evaluated using a queue-based simulation framework. Performance is analyzed using measures such as remaining queue length and maximum queue length.

## Technology Stack

- **Programming:** Python
- **Computer Vision:** OpenCV, YOLO-based detection and segmentation experiments
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib
- **Graph Modelling:** NetworkX
- **Development Environment:** VS Code, Google Colab

*The tools listed above reflect the technologies explored or used across the project; not every tool is necessarily part of every module.*

## Current Status

The project is under active development. The work so far has focused on developing the modelling approach, analyzing traffic conditions, constructing road-network representations, and experimenting with queue-based simulation and signal-timing strategies.

The longer-term objective is to integrate these components into a more comprehensive framework for modelling and evaluating urban traffic systems.

## Future Work

- Improve the integration of traffic observations with the road-network model.
- Investigate how congestion propagates between connected intersections.
- Validate queue estimates and simulation assumptions against real-world observations.
- Explore predictive models for estimating future traffic states.
- Extend the framework to additional intersections and potentially other Indian cities.

## Project Report

The research methodology, modelling approach, experiments, and findings are documented in the project report available in this repository.

## Motivation

I started this project to explore how ideas from artificial intelligence, graph theory, and mathematical modelling could be applied to a complex real-world system. It has been an opportunity to work across data analysis, modelling, computer vision, and simulation while investigating the challenges involved in representing real-world traffic digitally.

---

**Project Type:** Independent Research Project  
**Domain:** Artificial Intelligence, Urban Mobility, Traffic Modelling  
**Status:** Ongoing
