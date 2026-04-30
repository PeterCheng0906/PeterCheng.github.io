---
title: "Gomoku AI Engine — Minimax + Reinforcement Learning"
excerpt: "Two-phase AI engine for Gomoku (Five-in-a-Row): Phase 1 used Minimax with Alpha-Beta pruning and a custom evaluation function; Phase 2 extended it with self-play and Q-learning for adaptive competitive play."
collection: portfolio
date: 2025-03-31
permalink: /portfolio/gomoku-ai/
---

**Role:** Lead developer · **Affiliation:** Stanford University · **Period:** Sep 2024 – Mar 2025

[**View on GitHub →**](https://github.com/PeterCheng0906/Five-In-A-Row)

## Overview

A two-phase AI engine for Gomoku (Five-in-a-Row), built end-to-end across two academic terms. Phase 1 established a strong rule-based baseline; Phase 2 extended it with reinforcement learning to make the engine adaptive against a wider range of opponents.

## Phase 1 — Minimax with Alpha-Beta Pruning *(Sep 2024 – Dec 2024)*

- **Built a deterministic AI engine** using the Minimax algorithm with Alpha-Beta pruning to optimize decision-making in a deterministic game environment.
- **Designed a custom evaluation function** that scored board states based on potential five-in-a-row formations, blocking threats, and strategic positioning.
- **Implemented recursive tree search** to simulate future moves up to a configurable depth, with Alpha-Beta pruning dramatically cutting computation time.
- **Validated the engine** through human-AI matches and visual debugging tools; this phase laid the groundwork for the later reinforcement learning extension.

## Phase 2 — Reinforcement Learning for Competitive Strategy *(Sep 2024 – Mar 2025)*

- **Extended the core agent** by integrating reinforcement learning principles — specifically self-play and Q-learning — on top of the Minimax foundation.
- **Iteratively tuned hyperparameters and exploration strategies** including ε-greedy and learning-rate decay to improve performance.
- **Tested against human and AI opponents**, demonstrating strategic foresight, rapid convergence, and a design that scales to larger board sizes.
- **Future work** explores integration with policy/value networks for deep reinforcement learning.

## Why it matters

Game-AI projects are a clean way to show end-to-end algorithmic thinking: search, heuristics, evaluation design, and learning all in one system. This project also demonstrates how to layer learning-based methods on top of a strong rule-based core — a common pattern in real production systems where pure RL would be too brittle.

## Tech stack

Python · Minimax · Alpha-Beta pruning · Q-learning · self-play · ε-greedy exploration · game theory · heuristic search
