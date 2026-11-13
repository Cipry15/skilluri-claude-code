# Skill-uri Claude Code din cursurile AI

Skill-urile pe care le folosesc în [cursurile AI](https://cursuri-ai-ciprian.vercel.app). Un skill e un folder cu instrucțiuni pe care Claude Code îl citește ca să facă o sarcină într-un fel anume.

| Skill | Ce face | Cursul |
|---|---|---|
| `ig-human` | Rescrie textele generate de AI ca să sune omenește | Prompturi bune |
| `ig-plan` | Plan de postări pe Instagram pentru afacerea ta | AI pentru bani și muncă |
| `ig-profile` | Profil de Instagram care transformă vizitatorii în clienți | AI pentru bani și muncă |
| `ig-caption` | Descrieri de postări cu un singur îndemn clar | AI pentru bani și muncă |
| `ig-reel` | Structura unui Reel care ține oamenii până la final | Imagini și video cu AI |
| `animation-principles` | Mișcare care pare naturală în clipuri și animații | Imagini și video cu AI |

## Cum le instalezi

1. Descarcă repo-ul: butonul verde **Code → Download ZIP**, apoi dezarhivează.
2. Copiază folderul skill-ului dorit din `skills/` în `~/.claude/skills/` (pe Windows: `%USERPROFILE%\.claude\skills\`).
3. Repornește Claude Code. Scrie `/ig-human` (sau numele skill-ului) ori cere direct sarcina, iar Claude îl folosește singur.

Din terminal, pentru un singur skill:

```bash
mkdir -p ~/.claude/skills && cp -r skills/ig-human ~/.claude/skills/
```

Skill-urile `ig-*` citesc opțional fișierul `~/.claude/instagram/voice.md`, unde îți poți descrie tonul și publicul. Câteva au scripturi Python mici (doar biblioteca standard, fără internet).

## Surse și licențe

Nu sunt scrise de mine de la zero, ci alese și testate pentru cursuri:

- `ig-human`, `ig-plan`, `ig-profile`, `ig-caption`, `ig-reel`: din [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill), © 2026 Jake Schincariol, licență MIT.
- `animation-principles`: din [motion-design-skills](https://github.com/iart-ai/motion-design-skills), © 2026 iart.ai, licență MIT.

Textul licențelor e în `licente/` și în fiecare folder de skill. Le poți folosi gratuit, inclusiv comercial, păstrând aceste mențiuni.
