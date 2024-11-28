# Option Pricing Notebook

This notebook explores option pricing using the binomial model, the Black-Scholes equation, and Monte Carlo simulations.

## Introduction

Options are financial instruments whose value depends on an underlying asset (derivatives) like a stock or an ETF. They give the holder the right (but not the obligation) to buy or sell the underlying asset at a future date. This notebook focuses on pricing options using three main approaches: the binomial model, the Black-Scholes equation, and Monte Carlo simulations.

## Part 1: Binomial Model

In this section, I briefly explain the binomial model and provide a Python class that computes option prices on a binomial lattice for an option written on an underlying stock. The class accommodates both European and American options (call and put) and considers the possibility of dividends for the stock. I also simulate the stock price with a random walk and observe how the price of the option evolves over time.

## Part 2: Black-Scholes Equation

Moving to the continuous-time limit, this section describes how the price of an option can be modelled using the Black-Scholes equation. It also explains how the stock price can be simulated using geometric Brownian motion. In the simulation, I verify the expected agreement between the Black-Scholes approach and the binomial model.

## Part 3: Monte Carlo Simulations

Another method for pricing options is to simulate a large number of paths for the underlying asset's evolution and calculate the average payoff discounted to the present. This section provides a straightforward method to perform such simulations and compares the results to theoretical option prices.

## Usage

To use this notebook, open it in a Jupyter environment and run each cell sequentially. Modify parameters and inputs as needed to explore different scenarios and understand option pricing under various conditions.
