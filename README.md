# TARN — Tarentaise Transfer Radar (demo)

Tarentaise valley adaptation of BAK/ZUR: transfer-demand zones (Geneva/Lyon/Chambéry
airports, Moûtiers ski-train station, Courchevel, Méribel, Val Thorens, Bozel base),
hourly demand model, après-ski + changeover-day events, weather modifier.

Flight arrivals: **live GVA data** via mvr-proxy (shared AeroDataBox pool with BAK/SOF,
180 units/day budget) — falls back to a static demo dataset if the proxy or the daily
quota is unavailable.

Ground transport (SNCF/Moûtiers, ski-shuttle buses) not wired yet — see chat notes:
SNCF has a free real-time API but needs a signup token; no public API exists for the
regional ski-shuttle operators.
