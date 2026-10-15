# Lazurio Example Organization experiments

> **Fictional sample data.** The plans, prices and offers in this repository
> are fictional samples of Lazurio's reference Organization. Prices are
> placeholder values in square brackets (for example `[PILOT PRICE]`).

A module for experiment specs, run logs, metrics, results and stop/scale
decisions.

An experiment is the smallest safe test that can confirm or refute that a
chosen mechanism can make money for Lazurio Example Organization.

## Required parts of an experiment

- hypothesis
- target customer
- offer and channel
- success metric
- budget and time limit
- stop condition and scale condition
- legal, ToS and reputation check
- result and evidence

## Structure

- `checklists/`: a repeatable check before an experiment starts
- `shortlists/`: comparisons of candidates and the decision which test to run
  first
- `specs/`: concrete experiment specs ready for human approval
- `assets/`: working offers, outreach drafts and call scripts
- `templates/`: repeatable forms for intake and run logs
- `runs/`: run logs after an experiment starts

The agent may prepare materials, scoring, copy drafts and local assets.
External actions, contacting people, spending money and working with client
data require explicit human confirmation.
