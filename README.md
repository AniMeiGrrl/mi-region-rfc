# Michigan MeshCore Regions

This repository develops a shared region-scoping standard for Michigan MeshCore communities.

The draft treats regions as RF propagation and community domains, not political boundaries. Its purpose is to reduce unnecessary RF flooding while preserving useful connectivity at local, regional, statewide, and interstate scales.

## RFCs

- [RFC-001: Michigan MeshCore Regions](rfc/0001-michigan-regions.md) — Draft
- [RFC-001 Addendum A: Scoping Policy and Reference County Assignments](rfc/0001-addendum-a-scoping-and-county-reference.md) — Draft

## Current draft hierarchy

```text
midwest                      # USA Midwest
├── mi                       # Michigan
│   ├── mi-west              # West Michigan
│   │   ├── grr              # Grand Rapids
│   │   ├── azo              # Kalamazoo
│   │   ├── mkg              # Muskegon (example)
│   │   ├── bcr              # Battle Creek (proposed)
│   │   ├── bnh              # Benton Harbor (proposed)
│   │   └── hol              # Holland / Zeeland (proposed)
│   ├── mi-central           # Central Michigan
│   │   ├── thumb            # Thumb
│   │   ├── midstate         # Lansing / Mid-Michigan
│   │   ├── fnt              # Flint (proposed)
│   │   ├── hls              # Hillsdale (proposed)
│   │   ├── jxn              # Jackson (proposed)
│   │   ├── mbs              # Midland / Bay City / Saginaw (proposed)
│   │   ├── mpl              # Mount Pleasant (proposed)
│   │   ├── tws              # Tawas (proposed)
│   │   └── wbr              # West Branch (proposed)
│   ├── mi-east              # Eastern Michigan
│   │   ├── det              # Metro Detroit (example)
│   │   ├── adr              # Adrian (proposed)
│   │   ├── ann              # Ann Arbor (proposed)
│   │   ├── bdf              # Bedford Township (proposed)
│   │   ├── blu              # Port Huron / Marysville (proposed)
│   │   ├── bri              # Brighton / Howell (proposed)
│   │   └── lap              # Lapeer (proposed)
│   ├── mi-north             # Northern Michigan
│   │   ├── tvc              # Traverse City (example)
│   │   ├── alp              # Alpena / Rogers City (proposed)
│   │   ├── bgr              # Big Rapids (proposed)
│   │   ├── cad              # Cadillac (proposed)
│   │   ├── gld              # Gaylord / Charlevoix / Petoskey (proposed)
│   │   ├── gry              # Grayling / Kalkaska (proposed)
│   │   ├── hlk              # Houghton Lake (proposed)
│   │   ├── mac              # Mackinaw City / Cheboygan (proposed)
│   │   ├── man              # Manistee / Ludington / Frankfort (proposed)
│   │   └── mio              # Mio (proposed)
│   └── mi-upper             # Upper Peninsula
│       ├── mqt              # Marquette / Munising / Ishpeming (example)
│       ├── esc              # Escanaba / Gladstone (proposed)
│       ├── irm              # Iron Mountain (proposed)
│       ├── irw              # Ironwood (proposed)
│       ├── kwn              # Ontonagon / Houghton / L'Anse (proposed)
│       ├── msq              # Manistique (proposed)
│       ├── nby              # Newberry (proposed)
│       ├── soo              # Sault Ste. Marie (proposed)
│       └── sti              # St. Ignace (proposed)
├── il                       # Illinois (example)
├── in                       # Indiana (example)
└── wi                       # Wisconsin (example)
```

The city and neighboring-state examples illustrate how the model can scale; they do not establish hard boundaries or govern another community's regional structure.
