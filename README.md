<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img alt="zieludev. Indoor cycling on Linux. Below the name, the power bars of an interval workout: a warm-up, steady riding, four hard intervals and a cool-down." src="assets/banner-light.svg">
  </picture>
</p>

I build tools that make indoor cycling work on Linux. In practice that means Bluetooth LE, virtual
machines and containers, and a lot of shell and Python. I test what I publish and write down how it
works.

- **[rouvy-linux](https://github.com/zieludev/rouvy-linux)**: an unofficial launcher for the ROUVY
  indoor cycling app on Linux. One command boots a Windows VM, lends it your Bluetooth adapter and
  opens the app.
- **[phantomwatts](https://github.com/zieludev/phantomwatts)**: a virtual Bluetooth LE smart trainer
  (Fitness Machine, Cycling Power, Heart Rate) that needs no radio, for testing indoor cycling apps
  in virtual machines and CI. New, at v0.1.
- **[tapirpost](https://github.com/zieludev/tapirpost)**: a small headless CMS in Go. One binary with
  an HTTP API, SQLite or PostgreSQL, drafts and publishing, and an optional cache that does not
  serve stale content. New, at v0.1.
