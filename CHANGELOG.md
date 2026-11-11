# Changelog

## 0.5.7 (2026-11-11)
- Rivals answer your nitro: when you fire one, rivals close by fire theirs after a short reaction (better drivers more often).
- Catch-up now measured against your own car: when you're ahead, the front runners can reel in a player who is flat out on the straights (before, they topped out around 95% of a stock car in the Rookie Cup). Mid-pack rivals don't.
- Contenders: the two rivals leading the cup (or the two fastest in a first / free race) start on the front row, drive more cleanly, carry an extra nitro and get a fresh charge every lap.

## 0.5.6 (2026-11-11)
- Weather balance: rain and fog are rarer. On the rookie tracks a race now has rain about 1 in 4 times (was ~2 in 5) and fog about 1 in 10 (was ~1 in 4); mid-race changes happen about 1 in 6 races (was 1 in 3). STORM WOODS keeps its stormy character.

## 0.5.5 (2026-11-11)
- Nose-up jump frame follows the car setup: the tall wing shows as a plank across the trunk with its posts, the lip spoiler as a thick trunk edge, and low suspension now hides a tire row (high shows the gap, as before).

## 0.5.4 (2026-11-11)
- New nose-up car frame for jumps, from a hand sketch: the roof outline becomes the front with headlights, a wide windshield line with mirrors, pillars opening out to a squashed rear with smaller tail lights and wheels. Shown from takeoff to the peak (the half-tilt frame is gone).

## 0.5.3 (2026-11-11)
- Jumps: new nose-up animation. Off the ramp the car tilts half way, then fully up (seen almost from above as a trapezoid: headlights and hood far away at the top, windshield, roof, rear window, the rear face tilted down to a strip and 1 px narrower each side), then half way again and level at the peak.
- Speed lines burst out on takeoff and streak off the bottom of the car on the way up.

## 0.5.2 (2026-11-11)
- Jumps: the car noses up off the ramp (the hood and front show over the roof for the first time), then levels out at the top of the jump.

## 0.5.1 (2026-11-11)
- Broken road with a jump ramp (rolled per race, on a straight): warning signs and arrows painted on the ramp lane, then a stretch of potholes. Hit the ramp and you fly: the camera rides up with the car (the road drops out of frame and the horizon dips), the engine revs free, the music fades and slams back on landing.
- Landing depends on the suspension: high lands soft with a small hop, low slams down, bounces less and fishtails. Land short and you lose speed in the potholes.
- Missing the ramp costs speed in the potholes; high suspension and rally tires lose the least.
- Rivals decide whether to take the ramp (better drivers more often) and fly too; the police car doesn't jump.
- Birds: now and then one crosses your flight path. BIRD STRIKE costs a damage point.

## 0.5.0 (2026-11-11)
- Race conditions rolled for every race on the same layout: time of day (day, dusk with a big low sun, night with stars, moon and darker ground), weather (clear, fog, rain, storm, snow on the alpine track), dirt sections that move around, puddles on wet roads.
- Forecast on the track screen (*LATER: RAIN?*) and weather that can change mid race (rain starting, skies clearing, fog rolling in, snow falling), announced on the ticker. The road soaks fast and dries slowly; grip follows it, for you and for the rivals, and depends on your tires.
- Puddles: drag, a twitch of the wheel and a spray of water; rivals slow down in them too.
- Fog shortens the view; rain, storm and thick fog cover the sun, moon and stars.
- Garage before a race uses the rolled conditions (dry / wet / snow) for the tire stats.

## 0.4.9 (2026-11-11)
- FIRST! is now a small ticker message like the others (the jingle still plays).
- Wanted level shown as asterisks and dashes (`* - -`, `* * -`, `* * *`) instead of hollow stars.

## 0.4.8 (2026-11-11)
- Wanted level: 1 to 3 stars in the top right corner while the police chase you, with the fine you'd pay if caught right now. 1 star for speeding (stop when told: minimum fine), 2 for fleeing (ignoring the order, nitro, slingshot or cutting past it), 3 for hitting the cop or making it ram you. Escape and you pay nothing.
- Fines per star: Rookie $100 / $250 / $500, Pro $300 / $700 / $1200, Elite $800 / $1500 / $2500.

## 0.4.7 (2026-11-11)
- Lower police fines, about 10% of the cup's winning prize: Rookie $100, Pro $300, Elite $800 (busted is still double).

## 0.4.6 (2026-11-11)
- Rivals drive instead of just aiming at you: they read the next corners and brake before them, take the inside line, and follow the same grip rules as your car. Overcook a corner and they slide wide and scrub speed, more often on snow and rain.
- Each rival has a skill and an aggression value: better drivers commit to the racing line and misjudge grip less; only some drivers defend their line, and never mid-corner.
- Snow and rain tracks: rival base pace nudged up to make up for the careful cornering.

## 0.4.5 (2026-11-11)
- Fix: rivals no longer slide sideways on the grid before GO.
- Rivals: wider spread of pace and launch so the field strings out; smooth catch-up (rubber band) that pushes the front runners hardest when you lead and eases off a rival far ahead, so the lead can change hands.
- Police: top speed 1.04, starts further back at your speed; loses you after 1.8 s out of sight (faster on nitro) and doesn't forget instantly when it sees you again; gives up after 16 s of pursuit. In STOP NOW mode it swerves slower than you and needs a closer hit, so you can dodge it.
- Slipstream works behind the police car too.
- Taking the lead flashes FIRST! with a jingle; losing it shows LEAD LOST on the ticker.

## 0.4.4 (2026-11-10)
- Dynamic race music: speed, nitro, slingshot, slipstream, a police chase and the final lap push the song up (up to about 7% faster, arpeggios fill in, driving bass, ghost 16th hats); a crash calms it down for a few seconds, a wreck almost to drums and bass. Layers switch on the beat or bar so it stays in time. Menus play the songs as written.

## 0.4.3 (2026-11-10)
- Pause menu drops the music to 10%.
- Resuming a race starts a 3-2-1-GO countdown with the world frozen (you can rev the engine while you wait); the music fades back in on GO.

## 0.4.2 (2026-11-10)
- Speed lines are now 3D: each one is born far down the road and rushes at the camera, projected through the track, so they bend with curves and follow hills toward the real vanishing point.

## 0.4.1 (2026-11-10)
- Payout screen: after each career race the prize and fines count up, then the money rolls into your bank with a payday jingle (press A to skip the count).
- Cup end: the top 3 now get a bonus (Rookie $1500 / $700 / $300, Pro $5000 / $2500 / $1000, Elite $15000 / $7000 / $3000), counted into the bank the same way. Only the winner unlocks the next cup.

## 0.4.0 (2026-11-10)
- Burnout style nitro: near misses give a quarter charge, drafting slowly refills it; partial charges show in the pips.
- Much more visible speed lines while drafting, slingshotting and on nitro; draft zone a bit wider.
- Police are less predictable: each speed trap is manned 60% of laps, and a speeder gets chased 70% of the time.
- The police car collides with rivals and steers around traffic; rivals bump each other too.
- Arcade obstacles off the road: soft ones fly away, trees throw you back to the road edge, buildings nearly stop you.
- Wider road and a slightly smaller car hitbox to make overtaking easier.

## 0.3.3 (2026-11-10)
- Messages moved out of the way: a small ticker at the top of the screen; only the start countdown and FINISH stay big.
- The police talk from their car: small outlined text above the cop sprite.
- Pit lane on every circuit: drive through the right shoulder near the finish to repair damage for free.
- Dirt sections on Green Hills, Salt Flats and Mirage Run, new rally tires; ride height now matters (bumps cost speed with a low car).
- Track screens show dirt %, bumpiness and a suspension tip.
- Fix: in debt you can enter the free ROOKIE CUP again; debt shows as -$.

## 0.3.2 (2026-11-10)
- 1-bit page chrome around the screen: pixel logo, dithered bezel, square controls, About dialog.
- No more snow, rain, fog or lightning inside tunnels.
- GitHub Pages entry (`index.html` reads `version.json`).

## 0.3.1 (2026-11-10)
- E / Q nitro for two-hand play (W/S + arrows).
- Police can be outrun: 106% top speed, keeps its distance in front, only blocks while you are right behind it, gives up sooner.
- See-through warning signs (dimmed inside, thick frame, outlined text), big font only for short words, 30% shorter on screen.

## 0.3.0 (2026-11-10)
- Career: ROOKIE / PRO / ELITE cups, prize money, entry fees, debt rule.
- Garage: free setup (suspension, gears, wing) and part slots, live car preview, stat bars.
- Shop: tires (street, slick, rain, snow), engine stages, nitro, chassis, brakes, radar detector. Sell at 50%.
- Police speed traps on street circuits: chase, pull over, fines, busted.
- Slingshot draft with wind streaks, suspension bottoming out on dips.
- 3 rookie circuits, audio mixer (music / engine / SFX), progress saved in the browser.

## 0.2.2 (2026-11-10)
- Longer songs: bridge, echo variation and breakdown for every race theme.

## 0.2.1 (2026-11-10)
- Rounded the top corners of the player car.

## 0.2.0 (2026-11-10)
- Kick / snare / hat drum synthesis, 3 new songs, narrower cars, animated tail lights and tire tread.
- Skids, damage, explosion and respawn, difficulty levels, rival nitro and blocking, slipstream.

## 0.1.0 (2026-11-10)
- First prototype: 5 circuits, 4-channel chip audio, championship and free race on a simulated 128x64 OLED.
