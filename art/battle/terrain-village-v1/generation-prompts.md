# 소구역 시제품 생성 프롬프트 세트

2026-10-25 · built-in image_gen. CLI/API fallback 미사용. 아래는 생성에 사용한 요구 세트이며 결과를 자동 승인하지 않는다. 원본 PNG4장과 분리 파일은 manifest.json의 출처/상태/해시로 연결한다.

## 산악12유형 — source-mountains.png

Production game sprite atlas, transparent RGBA background, landscape1536×1024,4 columns×3 rows. One isolated terrain module per cell with generous transparent margins and no text. Reference: art/maps/kim-nangbi-v2.png. Warm brown ink outlines, rich hand-painted watercolor anime Korean terrain, moss/soil/grass/granite. Consistent2:1 isometric camera and upper-left light. Modular connected mountain surface artwork, not piles of identical rocks, not cubes, not3D. Organic irregular grass feathered edges. Row1: gentle grassy mountain foot apron; low rounded hill; high wooded hill with exposed stone; rocky mountain shoulder. Row2: irregular tall cliff face facing southeast; broad mountain summit with flat traversable grassy top; elongated connecting ridge along NE-SW axis; narrow gorge between uneven rock faces. Row3: ascending mountain footpath along NE-SW; curved outer corner; long gradual slope; eroded riverbank with pebbles and no water. No characters/UI/labels/checkerboard. Keep edges inside cells.

## 성문·민가 앞면 — source-buildings.png

Production sprite atlas for Korean hand-painted isometric strategy game. Exact4 columns3 rows, transparent RGBA background,1536×1024, generous separate margins. Reference: art/battle/infantry-lab-v1/source-props.png. Warm ink watercolor detailed style, upper-left sunlight,2:1 isometric projection. Row1 same Korean stone fortress gate with tiled gatehouse, open passage, independently drawn NE/NW/SE/SW orientations and stone connection stubs. Row2 same modest Korean thatched house with visible wooden entrance in NE/NW/SE/SW orientations. Row3 same modest dark tiled-roof house with four entrance orientations. No ground plate/scenery/grass background/text/labels/people. Actual independent drawings; no image rotation.

검수 결과: 요청과 달리 앞면2방향이 반복되었다. 실제 표시 방향에 따라 SE/SW와 변형으로 재분류했으며 NE/NW 완성품으로 등록하지 않았다.

## 바위8유형 — source-rocks.png

Isometric Korean strategy game sprite sheet, exact4 columns2 rows,8 isolated rock objects with generous transparent spacing, transparent background. Reference: art/maps/kim-nangbi-v2.png. Warm brown ink outlines, detailed watercolor anime hand painting,2:1 camera, upper-left light, gray granite/soil/green moss. Row1 large broad exposed bedrock; medium rounded irregular boulder; small loose stones cluster; flat weathered slab. Row2 moss-covered boulder; projecting cliff overhang; water-eroded river boulder with gravel but no water; irregular varied-size rock cluster. Distinct silhouettes, no repeated identical rock/cubes/text/labels/trees/humans/grass ground plate.

## 건축 후면 보완 — source-buildings-rear.png

Production Korean strategy game sprites, exact2 columns3 rows, transparent background, fixed2:1 camera and upper-left light, warm brown ink watercolor anime style. Reference: source-buildings.png. Rear views; near walls must not have entrance doors. Row1 stone gatehouse back courtyard side, passage NE left/NW right, tiled roof and wall stubs. Row2 thatched-house rear, hidden far NE entrance left/hidden far NW entrance right, near walls small windows only. Row3 tiled-roof house rear, hidden far NE/NW entrances. Independently drawn back structures, no mirrored facades. Six isolated sprites, wide padding, no ground/trees/text/labels/people.

검수 결과: 민가 후면 후보는 보존했으나 숨은 출입구는 실제 도로 포트와 검증하지 못했다. 성문은 통로가 가려져 확인할 수 없다.6개 모두 candidate로 분류하며 현재 맵 자동 배치에서 거부한다.

## 후처리와 원본 보존

tools/prepare-landscape-lab.cjs가 알파 연결 성분을 분리해 옆 원화의 조각을 배제한다. 그림을 회전/반전하거나 새 모양을 합성하지 않는다. 원본은 변경하지 않는다. 신규49개라는 집계는 기존 원화 재사용11개와 미검증/미사용 후보를 포함한 분리 파일 수이며49종 최종 승인 원화라는 의미가 아니다.


## 산허리·능선 일부 / mountain-flank.png

2026-10-25 최신 수정. One continuous impassable Korean mountain flank, part of an extensive mountain ridge. Transparent RGBA,2:1 isometric, warm brown ink watercolor anime terrain matching kim-nangbi-v2.png. Large mountain extends beyond top and right asset edges; crop peaks and far ridge. Organic descending lower-left foot with eroded granite, earth, moss and autumn vegetation. Continuous solid volume with branching ridges and varying cliff heights. No traversable flat summit, plateau, stairs, footpath, road, terraces, people, buildings, river, UI or text. Upper-left light. Never a whole isolated mountain or separated rock piles.
