# Ordered Escape Routing Research

## Quick Sort and Hierarchical Routing Completion for Ordered Escape Routing

Master's thesis research conducted at National Yunlin University of Science and Technology.

---

## Overview

Ordered Escape Routing (OER) is a critical problem in VLSI and PCB design, where routing paths must preserve predefined ordering constraints while maximizing routability.

Traditional SAT-based approaches can achieve high routability but often require significant computational resources.

This research proposes a routing framework that replaces SAT-based optimization with a Quick Sort driven routing strategy and a hierarchical routing methodology, achieving 100% routability while significantly reducing CPU execution time.

---

## Research Objectives

The goals of this research are:

* Improve routing efficiency for high-density pin arrays
* Achieve 100% routability under capacity constraints
* Reduce computational complexity compared with SAT-based methods
* Provide a scalable routing solution for Ordered Escape Routing problems

---

## Proposed Method

The proposed routing framework consists of three major stages:

### 1. Routability-Driven Pin Assignment

The pin array is partitioned into routing regions.

Quick Sort is utilized to efficiently assign transition pins while maintaining routing order constraints.

Main procedures include:

* Routing region partitioning
* Transition pin assignment
* Boundary pin assignment
* Routing region integration

---

### 2. Global Layer Assignment

After pin assignment, routing paths are assigned hierarchical priorities.

The layering process determines routing order and reduces potential routing conflicts.

---

### 3. Final Routing

Routing is completed from higher-priority layers to lower-priority layers.

A hierarchical routing strategy is applied to avoid crossing violations while preserving ordered routing requirements.

---

## Research Contributions

* Replaced SAT-based optimization with a Quick Sort based strategy
* Proposed a hierarchical routing methodology
* Achieved 100% routability on tested benchmarks
* Reduced CPU runtime compared with traditional SAT approaches
* Supported routing scenarios with capacity constraints greater than one

---

## Research Areas

* Ordered Escape Routing (OER)
* Routing Optimization
* Algorithm Design
* VLSI Design Automation
* PCB Routing
* Computational Optimization

---

## Tools and Technologies

* C++
* Algorithm Design
* Optimization Techniques
* Routing Analysis
* VLSI Design Automation

---

## Thesis Information

**Author:** Wei-Lun Xu

**Advisor:** Dun-Wei Cheng, Ph.D.

**Department:** Computer Science and Information Engineering

**University:** National Yunlin University of Science and Technology

**Year:** 2025

---

## Results

Experimental results demonstrate:

* 100% Routability
* Significant CPU Time Reduction
* Improved Scalability
* Efficient Ordered Routing Completion

This work provides an efficient alternative to traditional SAT-based Ordered Escape Routing solutions.
