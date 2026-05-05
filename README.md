# 2026 Capstone Checklist

This repo is the planning and execution board for my 2026 capstone drone project.

The actual implementation work is split across separate repositories (firmware and hardware). This repo tracks scope, milestones, and weekly progress.

## Project Goal

Build and validate a dual-MCU drone communication/control stack using:

- ESP32-S3 for high-level logic and UI
- SAMD21 for deterministic telemetry handling
- nRF links for wireless data transport

## What Is In This Repo

- architecture notes
- phase-by-phase checklist
- definition of done for each phase

## Active Implementation Repos

- `Capstone-Drone-Remote-Firmware`
- `Drone_FCU_Test_firmware`
- `Drone_remote_hardware`
- `SAMD_FCU_I2C`
- `NRF2401-Template`

## Current Focus

- Finish stable telemetry protocol between ESP32 and SAMD21
- Lock remote/FCU board revisions for manufacturing
- Improve test evidence quality (logs, videos, issue tracking)

## How I Use This Repo Weekly

1. Plan tasks.
2. Link code/hardware commits from other repos.
3. Mark completed milestones.
4. Record blockers and decisions.
