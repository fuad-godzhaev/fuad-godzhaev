# Hi, I'm Fuad 👋

Computer Science graduate (TU Dublin, 2026) based in Dublin. I like software that keeps working without someone else's server: peer-to-peer networking, self-hosting and privacy-respecting apps.

**Looking for a graduate or junior role in software, cloud or IT infrastructure in Ireland.**<br>
[LinkedIn](https://www.linkedin.com/in/fuad-godzhaev/) · [godzhaevfuad@gmail.com](mailto:godzhaevfuad@gmail.com)

### Right now

- Making my own version of Chess in Godot
- Cleaning up Aura so anyone can clone it and build it

---

### Featured projects

**[Aura](https://github.com/fuad-godzhaev/dating_app): a social app with no server behind it**<br>
<sub>Final-year project · Kotlin Multiplatform, Go (go-libp2p)</sub>

Every phone stores its own profile and helps deliver messages for other people, so no company holds anyone's data. I tested it as a dating app, because meeting strangers is the hardest thing to do without a central server.

- What surprised me: the distributed hash table was never the problem. Records stayed findable at 1,000 simulated nodes. The real limit is that only an estimated 17% of devices in Ireland can accept an incoming connection.
- Photos, not messages, turned out to be the bandwidth wall. Compressing them let each phone serve about four times as many profiles.

**[Gemini](https://github.com/fuad-godzhaev/aa-26/tree/AA_Assignment): a creature with a mind of its own** · [demo video](https://youtu.be/yA_7xuaNlWg)<br>
<sub>Autonomous Agents module · Godot 4, GDScript</sub>

A twin-bodied, glowing reef predator that hunts, gets curious, gets spooked, tires out and swims home to rest, with no scripted sequences. Its behaviour comes from steering behaviours, a needs-driven blackboard and a behaviour tree.

**[Cyber Runner](https://github.com/fuad-godzhaev/Endless-Runner): an endless runner you play with your voice** · [PC demo](https://youtu.be/eRsTGW3zypk) · [mobile demo](https://youtube.com/shorts/mWcLPC1slTo)<br>
<sub>Games Fleadh 2023 · Unreal Engine 5, Microsoft Azure</sub>

Built with a student team in 30 days. You steer the runner by saying commands out loud.

---

### My homelab

Where I learn infrastructure by breaking it first.

| What | Why |
|---|---|
| NAS on a TrueNAS-based OS, ZFS storage | Storage I control, with snapshots |
| Immich in Docker Compose | My own photo library instead of Google Photos |
| Pangolin + Traefik + WireGuard on a VPS | Remote access without exposing my home network |
| Bluesky personal data server (AT Protocol) | Hosting my own social media data |
| n8n | Small automations between my services |
| UniFi Wi-Fi | Roaming and Wi-Fi tuning |

### Lessons I learned the hard way

- **Test the riskiest piece in week one.** I first tried running an existing Node.js server inside the Android app. Native modules wouldn't cross-compile, and I only found out after building on top of it. I rewrote the data layer in Kotlin instead.
- **Say where every number comes from.** In Aura's report, each result is marked as measured on real code or estimated by a model, along with which way it's likely to be wrong. It made the conclusions much easier to defend.

### Outside of code

Photography, 3D printing my own designs, and building VR scenes in Godot. I speak English, Russian, Azerbaijani and Turkish.
