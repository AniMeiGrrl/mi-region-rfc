Michigan MeshCore Regions

**RFC-001**
Status: Draft

**Goal:**
Create a shared region-scoping standard for Michigan that reduces unnecessary RF flooding while preserving useful local, regional, statewide, and interstate connectivity.

## Scope and intent

This RFC establishes an initial shared hierarchy for naming Michigan MeshCore regions. Regions represent practical RF propagation and community domains rather than political boundaries. The hierarchy is intended to support useful communication at several geographic scales while avoiding traffic where it provides little value.

The design is intended to scale as communities and coverage grow. It does not assign ownership of a region, grant authority over a region's traffic, or provide a means for one community to take control of another. Region scopes are a shared coordination mechanism for limiting extraneous flooding while preserving useful connectivity and local autonomy.

This draft defines only the agreed initial path. Other statewide subregions are intentionally left unresolved.

## Initial hierarchy

```text
midwest
└── mi
    └── wmi
        └── grr
```

## Region meanings

### `midwest`

The `midwest` region is the broad interstate coordination domain containing Michigan and neighboring or nearby Midwestern MeshCore communities.

The commonly recognized [U.S. Census Midwest region](https://www.census.gov/programs-surveys/popest/guidance-geographies/terms-and-definitions.html) provides a geographic reference for this name. However, `midwest` is an RF propagation and community domain, not a strict adoption of Census boundaries. Participation should follow useful interstate connectivity, propagation relationships, and coordination between communities.

The region is intended for traffic that is genuinely useful across state or major regional boundaries. It is not a default destination for local or statewide traffic, nor does it grant any participant authority over traffic within another region.

### `mi`

The `mi` region uses Michigan's recognizable geographic boundary to provide a practical scope for statewide coordination. The state boundary is a reference for organizing traffic, not a claim that RF propagation or communities stop at the border.

The region is intended for traffic useful across Michigan that does not need the broader interstate scope of `midwest`. It does not assign ownership of Michigan traffic or authority over communities within the state.

### Initial subregions

- `wmi` — the West Michigan propagation and community domain.
- `grr` — the Grand Rapids-area local propagation and community domain.

These descriptions communicate intended scope; they do not establish political or rigid RF borders.

## Design principles

- Scope regions around useful RF propagation and real communities of communication.
- Preserve paths for local, regional, statewide, and interstate connectivity.
- Reduce unnecessary RF flooding by avoiding scopes broader than the communication need.
- Preserve local autonomy; participation in the hierarchy does not imply ownership or control of a region or its traffic.
- Allow the hierarchy to scale as propagation patterns and communities evolve.
- Use a clear hierarchy so broader and narrower domains remain understandable.
- Add regions only when their practical purpose and community are understood.
- Keep unsettled boundaries and statewide subdivisions open until there is agreement.

## Open questions

- What practical criteria should guide placement in `grr`, `wmi`, `mi`, or `midwest`?
- Where should the boundaries between propagation and community domains overlap or remain distinct?
- Which additional Michigan subregions are useful enough to define later?
- How should neighboring states and border communities coordinate at the `midwest` level?
- What evidence or community process should be required to add or revise a region?
