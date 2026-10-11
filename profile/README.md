<p align="center">
  <a href="https://mru.space">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://mru.space/assets/readme/mru-github-dark.gif">
      <img src="https://mru.space/assets/readme/mru-github-light.gif" alt="Mru" width="120" height="120">
    </picture>
  </a>
</p>

Mru builds software for unattended missions with no repair path. When a
processor fails and no one can replace it, Mru steps down from voting on three
replicas to comparing two, then to one replica that checks its own work, so the
system keeps doing useful work on the hardware that is left. Mru Flight is the
version for spacecraft. Mru Field is the version for equipment on Earth that
nobody can reach in time, such as deep-ocean sensors.

**Status: early prototype.** The decision core, a fault-injection demo and F´
components run on general-purpose processors. Nothing runs on flight hardware
yet.

- [flight](https://github.com/mruspace/flight): the decision core in Rust, F´
  components, the demo and the bench
- [dusk](https://github.com/mruspace/dusk): Monte Carlo simulator of
  redundancy policies, interactive at [dusk.mru.space](https://dusk.mru.space)
- [docs](https://github.com/mruspace/docs): source of
  [docs.mru.space](https://docs.mru.space)
- [whitepaper](https://github.com/mruspace/whitepaper): the architecture,
  [doi:10.5281/zenodo.20579438](https://doi.org/10.5281/zenodo.20579438)
- [website](https://github.com/mruspace/website): source of
  [mru.space](https://mru.space)

Questions: [contact@mru.space](mailto:contact@mru.space).
