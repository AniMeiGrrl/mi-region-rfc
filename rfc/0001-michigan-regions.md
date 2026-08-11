Michigan MeshCore Regions

**RFC-001**
Status: Draft

**Goal:**
Create a shared region-scoping standard for Michigan that reduces unnecessary RF flooding while preserving useful local, regional, statewide, and interstate connectivity.

## Scope and intent

This RFC establishes an initial shared hierarchy for naming Michigan MeshCore regions. Regions represent practical RF propagation and community domains rather than political boundaries. The hierarchy is intended to support useful communication at several geographic scales while avoiding traffic where it provides little value.

The design is intended to scale as communities and coverage grow. It does not assign ownership of a region, grant authority over a region's traffic, or provide a means for one community to take control of another. Region scopes are a shared coordination mechanism for limiting extraneous flooding while preserving useful connectivity and local autonomy.

This draft defines an initial Michigan hierarchy and illustrates how neighboring states could fit beneath `midwest`. The example state branches do not define or govern those states' regional structures.

## Initial hierarchy

```text
midwest
├── mi
│   ├── mi-west
│   │   └── grr
│   ├── mi-central
│   ├── mi-east
│   ├── mi-north
│   └── mi-upper
├── il (example)
├── wi (example)
└── in (example)
```

Michigan subregion names use a parent-first `mi-` prefix so they remain recognizable, group together, and avoid collisions with similarly named regions elsewhere. In this draft, `mi-north` refers to the northern Lower Peninsula and `mi-upper` refers to the Upper Peninsula.

## Region meanings

### `midwest`

The `midwest` region is the broad interstate coordination domain containing Michigan and neighboring or nearby Midwestern MeshCore communities.

The commonly recognized [U.S. Census Midwest region](https://www.census.gov/programs-surveys/popest/guidance-geographies/terms-and-definitions.html) provides a geographic reference for this name. However, `midwest` is an RF propagation and community domain, not a strict adoption of Census boundaries. Participation should follow useful interstate connectivity, propagation relationships, and coordination between communities.

The region is intended for traffic that is genuinely useful across state or major regional boundaries. It is not a default destination for local or statewide traffic, nor does it grant any participant authority over traffic within another region.

### `mi`

The `mi` region uses Michigan's recognizable geographic boundary to provide a practical scope for statewide coordination. The state boundary is a reference for organizing traffic, not a claim that RF propagation or communities stop at the border.

The region is intended for traffic useful across Michigan that does not need the broader interstate scope of `midwest`. It does not assign ownership of Michigan traffic or authority over communities within the state.

### `mi-west`

The `mi-west` region is the West Michigan coordination domain. Like `midwest`, the name describes a commonly understood geographic and community area with intentionally flexible edges; `mi-west` applies the same idea at a more local scale within Michigan.

Its practical scope should follow useful RF propagation, coverage, and relationships among West Michigan communities rather than fixed county or municipal boundaries. Communities near an edge may reasonably connect through the region when propagation and shared interests make that useful.

The region is intended for traffic useful across multiple West Michigan communities that is too broad for a local region such as `grr` but does not need statewide `mi` scope. It does not grant any participant ownership of West Michigan or authority over another community's traffic.

### `grr`

The `grr` region is the local coordination domain centered on the Grand Rapids metropolitan area, including nearby suburbs and communities connected to the metro area.

Its edges are intentionally flexible. Participation should follow useful local RF propagation, coverage, and community relationships rather than a fixed radius or a hard list of cities, townships, or counties. A nearby community may reasonably use `grr` when it shares local traffic and practical connectivity with the Grand Rapids area.

The region is intended for traffic useful within the greater Grand Rapids area that does not need the broader West Michigan scope of `mi-west`. It does not grant Grand Rapids or any participant ownership of the surrounding area or authority over another community's traffic.

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
