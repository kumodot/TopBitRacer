# Changelog

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
