# Option Pricing Notebook

This notebook explores option pricing using both the binomial model and the Black-Scholes equation.

## Introduction

Options are financial instruments whose value depends on an underlying asset (derivatives) like a stock or an ETF. They give the holder the right (but not the obligation) to buy or sell the underlying at a future date. This notebook focuses on pricing options using two main approaches: the binomial model and the Black-Scholes equation.

## Part 1: Binomial Model

In this section, I explain the binomial model briefly and provide a Python class that computes the prices on the binomial lattice of an option written on an underlying stock. The class accommodates both European and American options (call and put) and considers the possibility of dividends for the stock. I also simulate the stock price with a random walk and observe how the price of the option changes over time.

## Part 2: Black-Scholes Equation

Moving to the continuous time limit, this section describes how the price of an option can be described by the Black-Scholes equation, and the stock price can be simulated by a geometric Brownian motion. In the simulation, I verify the expected agreement between the Black-Scholes approach and the binomial model one.

## Usage

To use this notebook, simply open it in a Jupyter environment and run each cell sequentially. Modify parameters and inputs as needed to explore different scenarios and understand option pricing under various conditions.
