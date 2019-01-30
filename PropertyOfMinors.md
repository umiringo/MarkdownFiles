# Property of Minors

1. Pile
	* scale: 1
	* sprite: Pile
	* context
		* hp:  3
		* close: 0, 0
		* soClose: 0, 0
		* onceTrigger: false
		* dieAction: none
2. Sentry
	* scale: 1
	* sprite: sentry
	* context
		* hp: 5
		* close: 30, 15
		* soClose: 0, 0
		* onceTrigger: false
		* dieAction: none
	* move: LHGBB
		* speed: 0.5
		* needTurn: false
		* autoFace: false
3. Gunman
	* scale: 1.2
	* sprite: gunman
	* context
		* hp: 5
		* close: 30, 15
		* soClose: 10, 3
		* onceTrigger: false
		* dieAction: none
	* move: LHGBB
		* speed: 0.5
		* needTurn: true
		* autoFace: true
	* fire: auto
		* isBlocked: true
		* reloadCooldown: 1
		* bulletNumber: 1
		* fireCooldown: 0
		* bulletName: MonsterBullet
		* bulletDieFx: MonsterBulletFx
		* bulletMoveType: Linear
			* bulletSpeed: 10
	* Animator
		* soClose: gunman_fire
		* close: gunman_walk
		* normal: gunman_idle
4. SmallFort
	* scale: 1.2
	* sprite: smallfort
	* context
		* hp: 8
		* close: -1, -1
		* soClose: 30, 5
		* onceTigger: true
		* dieAction: none
	* fire: auto
		* isBlocked: true
		* reloadCooldown: 1
		* bulletNumber: 2
		* fireCooldown: 0.2
		* bulletName: MonsterBullet
		* bulletDieFx: MonsterBulletFx
		* bulletMoveType: Linear
			* bulletSpeed: 10
5. FlySentryBig
	* scale: 1.5
	* sprite: flysentrybig
	* context
		* hp: 5
		* close: 30, 3
		* soClose: 0, 0
		* onceTrigger: true
		* dieAction: none
	* move: SHSNN
		* flySpeed: 2
		* flyFrequency: 2
		* flyAmplitude: 2
6. FlySentrySmall
	* scale: 1
	* sprite: flysentrysmall
	* context
		* hp:  3
		* close: 30, 8 
		* soClose: 0, 0
		* onceTrigger: true
		* dieAction: none
	* move: TNSNN
		* speed: 2
7. Plane
	* scale: 1.5
	* sprite: plane
	* context
		* hp: 5
		* close: 30, 3
		* soClose: 0
		* onceTrigger: true
		* dieAction: none
	* move: LHSNN
		* speed: 3
8. DownFort
	* scale: 
	* sprite:
	* context
		* hp:
		* close:
		* soClose:
		* onceTrigger:
		* dieAction: none 
	

