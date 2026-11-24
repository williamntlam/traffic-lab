# Traffic Lab

**Exploring how individual decisions shape the behaviour of entire cities.**

## Motivation

Traffic Lab was inspired by my experience reading Jane Jacobs' *The Death and Life of Great American Cities* back in high school. Her ideas about urban planning, the complexity of cities, and the relationship between people and their environments left me with a fundamental question:

> How can we design great cities so that they leave an everlasting positive impact on the people who live in them?

Cities are complex systems shaped by millions of individual decisions. Even seemingly small changes to infrastructure, transportation policies, and human behaviour can have profound and sometimes unexpected consequences.

Traffic Lab is my attempt to explore these relationships through computer science, artificial intelligence, and simulation.

## What is Traffic Lab?

Traffic Lab is an experimental multi-agent traffic simulation and optimization platform built in Go. Each vehicle is represented as an autonomous agent with its own destination, driving behaviour, routing strategy, and decision-making logic.

By simulating thousands of interacting agents within a virtual city, Traffic Lab aims to investigate how individual decisions contribute to collective behaviour, traffic congestion, and overall urban efficiency.

The platform is designed to provide an experimental environment for testing infrastructure changes, transportation policies, and intelligent traffic management strategies without imposing their consequences on real communities.

## Research Questions

- How does individual decision-making influence city-wide traffic patterns?
- Can decentralized agents collectively optimize traffic without a central authority?
- Why do traffic jams emerge even in the absence of accidents or road closures?
- Can adding more roads make traffic congestion worse?
- How can intelligent traffic signals improve transportation efficiency?
- How do selfish and cooperative agents affect the performance of a city?
- Can AI autonomously identify urban bottlenecks, formulate hypotheses, and evaluate potential solutions?

## Planned Features

- High-performance, concurrent simulation engine written in Go.
- Autonomous vehicle agents with configurable driving behaviours.
- Dynamic routing and congestion-aware navigation.
- Adaptive traffic signals and intersection management.
- Interactive city visualization and traffic heatmaps.
- Real-world road network integration through OpenStreetMap.
- Distributed simulation and experiment execution.
- AI-powered traffic analysis and urban planning agents.
- Reproducible experiments with quantitative performance metrics.

## Engineering Objectives

Beyond urban planning and traffic optimization, Traffic Lab serves as a personal learning environment for exploring fundamental computer science and engineering concepts:

- Concurrency and parallel computing
- Distributed systems
- Graph theory and routing algorithms
- Game theory and emergent behaviour
- Queueing theory and resource scheduling
- Multi-agent artificial intelligence
- Reinforcement learning
- High-performance computing
- Cloud infrastructure and Kubernetes
- System observability and performance optimization

Rather than adopting technologies for their own sake, the project aims to introduce them as solutions to genuine engineering problems, understanding the constraints, alternatives, and trade-offs behind each architectural decision.

## Vision

Traffic Lab is ultimately about more than simulating cars. It is about understanding how complex systems emerge from simple interactions and exploring how technology can help us design better environments for people.

The long-term vision is to create an accessible virtual laboratory where developers, researchers, and urban planners can experiment with ideas, challenge assumptions, and investigate how cities can become more efficient, sustainable, and human-centered.

**Better cities begin with a better understanding of the systems that shape them.**
