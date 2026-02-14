# FM Stem Alliance Mechanical Models

The directory structure should be something like the one below.

Mechanical/
├── .gitignore               # Ignores CAD temp files (.lock, .tmp, etc.)
├── README.md                # Documentation on how to use the library
├── Library/                 # The "Gold Standard" re-usable parts
│   ├── COTS/                # Commercial Off-The-Shelf (Vex, Rev, WCP)
│   │   ├── Motors/
│   │   ├── Gearboxes/
│   │   └── Sensors/
│   └── Standards/           # Your team's custom re-usable designs
│       ├── Battery_Mounts/
│       ├── Electronics_Boards/
│       └── Bumper_Hardware/
├── Seasons/                 # Year-specific robot designs
│   ├── 2025_Reefscape/
│   │   ├── Assemblies/      # Full robot, Elevator, Intake
│   │   └── Parts/           # Unique custom parts for this year
│   └── 2026_Current_Game/
└── Tools/                   # Scripts for exporting BOMs or weight checks