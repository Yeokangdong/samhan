# 보병/전장 원화 생성 기록

2026-10-25 · built-in image_gen · 모든 호출 transparent_background=true. 외부 API/CLI는 사용하지 않았다. 아래 프롬프트를 사용하고, 별도 Python 단계에서 연결 성분 정리·프레임 분할·발 접지 정렬·아틀라스 구성을 수행했다. 그림 자체를 기존 정면 원화 축소로 대체하지 않았다.

## source-core.png

참조: art/characters/deployment-strict-front-v3/individual/alcheon.png

Create a production GAME SPRITE SHEET of this exact silver-haired female Korean infantry general Alcheon, retaining short wavy silver hair, gold circlet, red-orange eyes, ornate yellow-gold lamellar armor, ivory fur cape, short steel sword in RIGHT hand and round dark gold shield in LEFT hand. Redraw at 2.3 heads tall, hand-painted anime SD, warm brown crisp outlines, orthographic isometric 30 degree elevation. Transparent background, no text, no shadows, no borders. EXACT REGULAR GRID 8 COLUMNS by 4 ROWS, 32 separate complete characters, every pose has generous transparent margin, same head size and feet baseline within cells. Row1 facing southeast (screen down-right, visible face), row2 southwest (down-left visible face), row3 northeast (up-right genuine BACK view with back hair/cape), row4 northwest (up-left genuine BACK view). Never mirror front into rear. Each row columns: 1 idle ready stance; 2 walk left foot forward right foot back; 3 walk right foot forward left foot back; 4 sword attack windup raised sword twisting body; 5 sword strike fully extended toward facing direction; 6 sword recover lowered blade; 7 shield guard braced and shield raised; 8 hit recoil leaning backward. Maintain same sword right hand shield left hand physically in all directions. Entire character incl weapons inside each cell, all sprites same scale, no scenery, no extra figures. Large high resolution landscape sheet with eight evenly spaced columns and four evenly spaced rows. Use reference as identity not as a pasted or miniaturized image.

기본 공격 칸의 검 끝 여백은 불충분하여 최종 동작은 아래 source-attack 시트로 교체했다. 보행도 source-walk 시트로 보강했다.

## source-extra.png

참조: 같은 알천 원화.

GAME SPRITE SHEET, exact referenced female Alcheon silver short wavy hair gold circlet orange eyes gold lamellar armor ivory fur cape steel short sword RIGHT hand round dark golden shield LEFT hand. Hand drawn anime SD 2.3 heads tall, orthographic 30deg isometric quarter view. EXACT 4 columns x4 rows of separate COMPLETE FULL BODY figures at identical scale with generous transparent gaps. ROW1 down-right facing visible face; ROW2 down-left facing visible face; ROW3 up-right facing true back hair and fur cape; ROW4 up-left facing true back. COLUMNS in every row: 1 running left knee up and right leg extended back; 2 running opposite right knee up left leg extended back; 3 dodging sideways crouched low with shield; 4 fallen defeated lying on side on ground with sword and shield still held, clearly face or back matches row orientation. Never mirror front to make back. Every figure entirely inside each cell with large empty border. No text no grid no scenery no shadows. Transparent alpha.

## source-props.png

참조: art/maps/iso-objects-v2/clean/scenery-a.png

Create a 2 by 2 game object sprite sheet matching the reference's warm brown outlined hand-painted Korean historical tactical RPG isometric art, orthographic 30 degree elevation exact 2:1 isometric ground axes. Four full independent objects with very large empty transparent margins, no ground scenery, no labels. Top left: pointed log wooden palisade 6 sturdy irregular stakes lashed by rope, spans screen upper-left to lower-right (isometric X axis slope +0.5). Top right: same palisade other axis screen upper-right to lower-left slope -0.5, independently painted. Bottom left: small wooden footbridge with detailed worn wooden planks and low rope railings, length along screen upper-left to lower-right slope +0.5, no water. Bottom right: same wooden bridge length along other diagonal slope -0.5. Rich wood grain, weathered joints and moss, high quality matching existing buildings. Do not include any extra objects, trees, ground tiles or background. Transparent alpha.

## source-walk.png

참조: 같은 알천 원화.

Production WALK ANIMATION SPRITE SHEET 4 columns x4 rows. Same silver-haired female Korean Alcheon in gold circlet, orange eyes, ornate gold lamellar armor, ivory fur cape, steel sword in RIGHT hand round black-gold shield LEFT. Hand painted warm brown outline anime SD 2.3 heads tall. Orthographic 30deg elevated camera. Row1 facing screen DOWN RIGHT, row2 facing DOWN LEFT, row3 facing UP RIGHT genuine BACK, row4 facing UP LEFT genuine BACK. Every row FOUR DISTINCT successive walking frames: col1 left foot far forward heel contact right foot behind; col2 weight on left foot right knee passing forward; col3 right foot far forward contact left foot behind; col4 weight on right foot left knee passing forward. Legs visibly walking, alternating opposing legs, hips rotate subtly, arms equipped so restrained counter motion, head not bobbing greatly. Identical head/body scale all cells, feet same baseline in each cell, complete sword shield cape never cut. LARGE even transparent gutters between characters; each figure centered in its own equal grid cell. No background ground shadows labels borders grid. True transparent alpha. Preserve identity and clothing details.

## source-attack.png

참조: 같은 알천 원화.

Production sword ATTACK game sprite sheet exactly 3 COLUMNS x4 ROWS. Reference exact Alcheon female silver wavy short hair orange eyes golden headband gold detailed lamellar armor white ivory fur cape straight steel short sword RIGHT hand round gold shield LEFT hand, 2.3 heads tall hand drawn SD warm brown crisp outlines. True elevated orthographic 30-degree isometric. Row1 faces DOWN RIGHT (southeast), row2 DOWN LEFT southwest, row3 UP RIGHT northeast genuine back view, row4 UP LEFT northwest genuine back. Each row col1 attack wind-up with complete sword raised diagonally BEHIND HEAD; col2 powerful cutting downward-forward slash fully extended; col3 recovery with sword lowered and shield ready. Maintain silhouette identity, same head size all frames, consistent handedness, feet planted same baseline. VERY IMPORTANT LARGE TRANSPARENT GAPS and 20 percent empty margin all around every cell, including ample EMPTY SPACE ABOVE SWORD TIP, no cropped weapons anywhere. Every pose fits entirely inside its own separate cell. Do not stretch arm or weapon into adjacent cell. No text labels grid shadow floor scenery. Transparent alpha.
