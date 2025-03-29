# Maya Project Structure

This repository outlines a standard folder structure for organizing Maya projects, facilitating efficient asset management and collaboration.

## Folder Hierarchy

Maya_Project/                                <!-- Root project directory -->
├── assets/                                  <!-- Contains all reusable elements like characters and props -->
│   ├── characters/                          <!-- Directory for all character assets -->
│   │   ├── char_A/                          <!-- Character A asset directory -->
│   │   │   ├── model/                       <!-- Geometry and modeling files -->
│   │   │   ├── rig/                         <!-- Rigging setups -->
│   │   │   ├── textures/                    <!-- Textures specific to char_A -->
│   │   │   └── lookdev/                     <!-- Look development (shading/material tests) -->
│   │   ├── char_B/                          <!-- Character B asset directory -->
│   │   └── char_C/                          <!-- Character C asset directory -->
│   └── props/                               <!-- Directory for props used in scenes -->
│       └── ...                              <!-- Additional props go here -->
│
├── scenes/                                  <!-- Contains shot-specific animation and scene setups -->
│   ├── scene_01/                            <!-- Scene 01 content -->
│   │   ├── anim/                            <!-- Animation files for scene 01 -->
│   │   ├── layout/                          <!-- Camera, staging, and blocking setups -->
│   │   ├── lighting/                        <!-- Lighting configurations -->
│   │   └── render/                          <!-- Final render scenes or output for scene 01 -->
│   └── scene_02/                            <!-- Scene 02 content -->
│       ├── anim/                            <!-- Animation files for scene 02 -->
│       ├── layout/                          <!-- Camera and shot layout setups -->
│       ├── lighting/                        <!-- Lighting configurations for scene 02 -->
│       └── render/                          <!-- Render output for scene 02 -->
│
├── sourceimages/                            <!-- Stores image files used as textures or references -->
│   └── textures/                            <!-- Shared texture files used across multiple assets -->
│
├── images/                                  <!-- Contains playblasts, snapshots, and preview renders -->
├── renderData/                              <!-- Maya's internal render settings and data -->
├── scripts/                                 <!-- Custom MEL/Python scripts for tools or automation -->
└── cache/                                   <!-- Simulation caches like Alembic or nCache -->
