    hud_render_textures:
        or:
          - title: built-in
            or:
              - title: 'Apace'
                sprite_location:
                    const: "origins:textures/gui/sprites/hud_render/apace/resource_bar.png"
                bar_index:
                    or:
                      - title: '00 - Gunpowder'
                        const: 0
                      - title: '01 - Water Droplet'
                        const: 1
                      - title: '02 - Lightning Bolt'
                        const: 2
                      - title: '03 - Purple X'
                        const: 3
                      - title: '04 - Wings'
                        const: 4
                      - title: '05 - Spiderweb'
                        const: 5
                      - title: '06 - Ender Pearl'
                        const: 6
                      - title: '07 - Fire'
                        const: 7
                      - title: '08 - Vine'
                        const: 8
              - title: 'Huang'
                or:
                  - title: '01 - Symbols'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/huang/resource_bar_01.png"
                    bar_index:
                        or:
                          - title: '00 - Charge Beam'
                            const: 0
                          - title: '01 - Up Arrow - Dark Blue'
                            const: 1
                          - title: '02 - Spear'
                            const: 2
                          - title: '03 - Rocket - Light Blue'
                            const: 3
                          - title: '04 - Heart'
                            const: 4
                          - title: '05 - Ghost'
                            const: 5
                          - title: '06 - Totem of Undying'
                            const: 6
                          - title: '07 - Fire Charge'
                            const: 7
                          - title: '08 - Tornado'
                            const: 8
                          - title: '09 - White Rabbit'
                            const: 9
                          - title: '10 - Tidal Wave'
                            const: 10
                          - title: '11 - Igloo'
                            const: 11
                          - title: '12 - Ice Ball'
                            const: 12
                          - title: '13 - Sandstone'
                            const: 13
                          - title: '14 - Sun'
                            const: 14
                          - title: '15 - Wither Rose'
                            const: 15
                          - title: '16 - Red Sand'
                            const: 16
                          - title: '17 - Netherite Hoe'
                            const: 17
                          - title: '18 - Iron Heart'
                            const: 18
                          - title: '19 - Beacon'
                            const: 19
                          - title: '20 - Runner'
                            const: 20
                          - title: '21 - The World'
                            const: 21
                          - title: '22 - Copper Coin'
                            const: 22
                          - title: '23 - Tonic - Purple'
                            const: 23
                          - title: '24 - Emerald'
                            const: 24
                  - title: '02 - Symbols'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/huang/resource_bar_02.png"
                    bar_index:
                        or:
                          - title: '00 - Steel Diamond'
                            const: 0
                          - title: '01 - Clock'
                            const: 1
                          - title: '02 - Bomb'
                            const: 2
                          - title: '03 - Battery'
                            const: 3
                          - title: '04 - Scorpion'
                            const: 4
                          - title: '05 - Red Lightning'
                            const: 5
                          - title: '06 - Elder Guardian'
                            const: 6
                          - title: '07 - Werewolf'
                            const: 7
                          - title: '08 - Tree'
                            const: 8
                          - title: '09 - Glaciers'
                            const: 9
                          - title: '10 - Desert'
                            const: 10
                          - title: '11 - Gun'
                            const: 11
                          - title: '12 - Knife'
                            const: 12
                          - title: '13 - Backpack'
                            const: 13
                          - title: '14 - Withering Heart'
                            const: 14
                          - title: '15 - Wildfire'
                            const: 15
                          - title: '16 - Water'
                            const: 16
                          - title: '17 - Moon'
                            const: 17
                          - title: '18 - Cooked Beef'
                            const: 18
                          - title: '19 - Dark Blue Mushroom'
                            const: 19
                          - title: '20 - Buttercup'
                            const: 20
              - title: 'Isaac Fanta'
                or:
                  - title: '01 - Numbers'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/isaacfanta/resource_bar_01.png"
                    bar_index:
                        or:
                          - title: '00 - Red 1'
                            const: 0
                          - title: '01 - Dark Blue 2'
                            const: 1
                          - title: '02 - Green 3'
                            const: 2
                          - title: '03 - Yellow 4'
                            const: 3
                          - title: '04 - Orange 5'
                            const: 4
                          - title: '05 - Light Blue 6'
                            const: 5
                          - title: '06 - Pink 7'
                            const: 6
                          - title: '07 - Magenta 8'
                            const: 7
                          - title: '08 - Purple 9'
                            const: 8
                  - title: '02 - Symbols'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/isaacfanta/resource_bar_02.png"
                    bar_index:
                        or:
                          - title: '00 - Bone'
                            const: 0
                          - title: '01 - Broken Bone'
                            const: 1
                          - title: '02 - Clock'
                            const: 2
                          - title: '03 - White R'
                            const: 3
                          - title: '04 - White L'
                            const: 4
                          - title: '05 - Blue P'
                            const: 5
                          - title: '06 - Miku'
                            const: 6
              - title: 'Spider Kolo'
                or:
                  - title: '01 - Colored Orbs'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/spiderkolo/resource_bar_01.png"
                    or:
                      - title: '00 - Gold Diamond'
                        bar_index:
                            const: 0
                      - title: '01 - Emerald Diamond'
                        bar_index:
                            const: 1
                      - title: '02 - Water Orb'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Water Orb'
                                const: 0
                              - title: '1 - Water Orb'
                                const: 1
                      - title: '03 - Lava Orb'
                        bar_index:
                            const: 3
                        icon_index:
                            or:
                              - title: '0 - Lava Orb'
                                const: 0
                              - title: '1 - Lava Orb - Specular Highlight'
                                const: 1
                      - title: '04 - Ice Orb'
                        bar_index:
                            const: 4
                        icon_index:
                            or:
                              - title: '0 - Ice Orb'
                                const: 0
                              - title: '1 - Ice Orb'
                                const: 1
                      - title: '05 - Blood'
                        bar_index:
                            const: 5
                      - title: '06 - Creeper Face'
                        bar_index:
                            const: 6
                      - title: '07 - Brown Mushroom'
                        bar_index:
                            const: 7
                      - title: '08 - Red Mushroom'
                        bar_index:
                            const: 8
                        icon_index:
                            or:
                              - title: '0 - Red Mushroom'
                                const: 0
                              - title: '1 - Blank'
                                const: 1
                              - title: '2 - White Orb Upper Half'
                                const: 2
                      - title: '09 - White Orb'
                        bar_index:
                            const: 9
                        icon_index:
                            or:
                              - title: '0 - White Orb'
                                const: 0
                              - title: '1 - Blank'
                                const: 1
                              - title: '2 - White Orb Lower Half'
                                const: 2
                      - title: '10 - Orange Orb'
                        bar_index:
                            const: 10
                      - title: '11 - Purple Orb'
                        bar_index:
                            const: 11
                      - title: '12 - Blue Orb'
                        bar_index:
                            const: 12
                      - title: '13 - Gold Orb'
                        bar_index:
                            const: 13
                      - title: '14 - Green Orb'
                        bar_index:
                            const: 14
                      - title: '15 - Pink Orb'
                        bar_index:
                            const: 15
                      - title: '16 - Charcoal Orb'
                        bar_index:
                            const: 16
                      - title: '17 - Gray Orb'
                        bar_index:
                            const: 17
                      - title: '18 - Navy Orb'
                        bar_index:
                            const: 18
                      - title: '19 - Violet Orb'
                        bar_index:
                            const: 19
                      - title: '20 - Dark Blue Orb'
                        bar_index:
                            const: 20
                      - title: '21 - Brown Orb'
                        bar_index:
                            const: 21
                      - title: '22 - Dark Green Orb'
                        bar_index:
                            const: 22
                      - title: '23 - Dark Red Orb'
                        bar_index:
                            const: 23
                      - title: '24 - Black Orb'
                        bar_index:
                            const: 24
                  - title: '02 - Tools'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/spiderkolo/resource_bar_02.png"
                    or:
                      - title: '00 - Iron Shield'
                        bar_index:
                            const: 0
                      - title: '01 - Iron Sword'
                        bar_index:
                            const: 1
                      - title: '02 - Leather Boots'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Leather Boot'
                                const: 0
                              - title: '1 - Leather Ankle Boot'
                                const: 1
                      - title: '03 - Iron Pickaxe'
                        bar_index:
                            const: 3
                      - title: '04 - Iron Axe'
                        bar_index:
                            const: 4
                      - title: '05 - Iron Mace'
                        bar_index:
                            const: 5
                      - title: '06 - Tin Cylinder'
                        bar_index:
                            const: 6
                      - title: '07 - Eye'
                        bar_index:
                            const: 7
                      - title: '08 - Shining Diamond'
                        bar_index:
                            const: 8
                        icon_index:
                            or:
                              - title: '0 - Small Diamond'
                                const: 0
                              - title: '1 - Large Diamond'
                                const: 1
                              - title: '2 - Small Diamond'
                                const: 2
                      - title: '09 - Red Cross'
                        bar_index:
                            const: 9
                      - title: '10 - Green Potion'
                        bar_index:
                            const: 10
                      - title: '11 - Gold Potion'
                        bar_index:
                            const: 11
                      - title: '12 - Red Potion'
                        bar_index:
                            const: 12
                      - title: '13 - Blue Potion'
                        bar_index:
                            const: 13
                      - title: '14 - Redstone Dust'
                        bar_index:
                            const: 14
                      - title: '15 - Water'
                        bar_index:
                            const: 15
                      - title: '16 - Magnet'
                        bar_index:
                            const: 16
                      - title: '17 - White Skull'
                        bar_index:
                            const: 17
                      - title: '18 - Marsh Skull'
                        bar_index:
                            const: 18
                      - title: '19 - Obsidian Skull'
                        bar_index:
                            const: 19
                      - title: '20 - Green Skull'
                        bar_index:
                            const: 20
                      - title: '21 - Slime'
                        bar_index:
                            const: 21
                      - title: '22 - Leaf'
                        bar_index:
                            const: 22
                      - title: '23 - Block Moon'
                        bar_index:
                            const: 23
                      - title: '24 - Block Sun'
                        bar_index:
                            const: 24
                  - title: '03 - Icons'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/spiderkolo/resource_bar_03.png"
                    or:
                      - title: '00 - Hashtag'
                        bar_index:
                            const: 0
                        icon_index:
                            or:
                              - title: '00 - 6-Point 2x1'
                                const: 0
                              - title: '01 - Blank'
                                const: 1
                              - title: '02 - Diamond'
                                const: 2
                              - title: '03 - Cross'
                                const: 3
                              - title: '04 - Hashtag - Large'
                                const: 4
                              - title: '05 - Hashtag'
                                const: 5
                              - title: '06 - Spiny Diamond'
                                const: 6
                              - title: '07 - Round'
                                const: 7
                              - title: '08 - Blank'
                                const: 8
                              - title: '09 - Round'
                                const: 9
                              - title: '10 - Cross - Tilted'
                                const: 10
                              - title: '11 - 6-Point 1x2 Large'
                                const: 11
                              - title: '12 - 6-Point 2x1 Large'
                                const: 12
                              - title: '13 - 6-Point 1x2 Small'
                                const: 13
                              - title: '14 - 6-point 2x1 Small'
                                const: 14
                      - title: '01 - Chest'
                        bar_index:
                            const: 1
                      - title: '02 - Cat Yarn'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Red Yarn'
                                const: 0
                              - title: '1 - Orange Cat'
                                const: 1
                      - title: '03 - Cheese Mouse'
                        bar_index:
                            const: 3
                        icon_index:
                            or:
                              - title: '0 - Cheese Wedge'
                                const: 0
                              - title: '1 - White Mouse'
                                const: 1
                      - title: '04 - Rat'
                        bar_index:
                            const: 4
                        icon_index:
                            or:
                              - title: '0 - Gray Rat'
                                const: 0
                              - title: '1 - Brown Rat'
                                const: 1
                      - title: '05 - Bone'
                        bar_index:
                            const: 5
                      - title: '06 - Dough'
                        bar_index:
                            const: 6
                        icon_index:
                            or:
                              - title: '0 - Dough'
                                const: 0
                              - title: '1 - Egg'
                      - title: '07 - Nether Portal'
                        bar_index:
                            const: 7
                        icon_index:
                            or:
                              - title: '0 - Portal - Small'
                                const: 0
                              - title: '1 - Portal - Large'
                                const: 1
                      - title: '08 - Treasure Map'
                        bar_index:
                            const: 8
                      - title: '09 - Hourglass Clock'
                        bar_index:
                            const: 9
                        icon_index:
                            or:
                              - title: '0 - Hourglass - Slim'
                                const: 0
                              - title: '1 - Hourglass - Wide'
                                const: 1
                              - title: '2 - Hourglass - Slim - Right-Aligned'
                                const: 2
                              - title: '3 - Clock'
                                const: 3
                      - title: '10 - Rose'
                        bar_index:
                            const: 10
                      - title: '11 - Oak Tree'
                        bar_index:
                            const: 11
                      - title: '12 - Diamond'
                        bar_index:
                            const: 12
                      - title: '13 - Music Note'
                        bar_index:
                            const: 13
                        icon_index:
                            or:
                              - title: '0 - 1/8 Note - Bold'
                                const: 0
                              - title: '1 - 1/8 Note'
                                const: 1
                              - title: '2 - 1/8 Note - Faded'
                                const: 2
                      - title: '14 - Goggles'
                        bar_index:
                            const: 14
                        icon_index:
                            or:
                              - title: '0 - Goggles - Blue Lens'
                                const: 0
                              - title: '1 - Goggles - White Lens'
                                const: 1
                      - title: '15 - Sponge'
                        bar_index:
                            const: 15
                      - title: '16 - Up Arrow - Light Blue'
                        bar_index:
                            const: 16
                        icon_index:
                            or:
                              - title: '0 - Up Arrow - Wide'
                                const: 0
                              - title: '1 - Up Arrow - Slim'
                                const: 1
                      - title: '17 - Down Arrow - Red'
                        bar_index:
                            const: 17
                        icon_index:
                            or:
                              - title: '0 - Down Arrow - Wide'
                                const: 0
                              - title: '1 - Down Arrow - Slim'
                                const: 1
                      - title: '18 - Stars'
                        bar_index:
                            const: 18
                      - title: '19 - Gray Dye'
                        bar_index:
                            const: 19
                      - title: '20 - Charcoal'
                        bar_index:
                            const: 20
                      - title: '21 - Green Clone'
                        bar_index:
                            const: 21
                      - title: '22 - Pattern'
                        bar_index:
                            const: 22
                      - title: '23 - Feather'
                        bar_index:
                            const: 23
                      - title: '24 - Shears'
                        bar_index:
                            const: 24
              - title: 'Stella'
                sprite_location:
                    const: "origins:textures/gui/sprites/hud_render/stella/resource_bar_01.png"
                bar_index:
                    or:
                      - title: '00 - Pride Orb - LGBT'
                        const: 0
                      - title: '01 - Pride Orb - Trans'
                        const: 1
                      - title: '02 - Pride Orb - Lesbian'
                        const: 2
                      - title: '03 - Pride Orb - Non-Binary'
                        const: 3
                      - title: '04 - Pride Orb - Bi'
                        const: 4
                      - title: '05 - Pride Orb - Pan'
                        const: 5
                      - title: '06 - Pride Orb - Gay'
                        const: 6
                      - title: '07 - Pride Orb - Inter'
                        const: 7
                      - title: '08 - Pride Orb - Ace'
                        const: 8
                      - title: '09 - Pride Orb - Demi'
                        const: 9
              - title: 'Vevehki'
                or:
                  - title: '01 - Resources and Mobs'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/vevehki/resource_bar_01.png"
                    or:
                      - title: '00 - Orb of Origin'
                        bar_index:
                            const: 0
                      - title: '01 - Copper'
                        bar_index:
                            const: 1
                        icon_index:
                            or:
                              - title: '0 - Copper Ingot'
                                const: 0
                              - title: '1 - Copper Block'
                                const: 1
                              - title: '2 - Copper Block - Exposed'
                                const: 2
                              - title: '3 - Copper Block - Weathered'
                                const: 3
                              - title: '4 - Copper Block - Oxidized'
                                const: 4
                              - title: '5 - Copper Ore - Raw'
                                const: 5
                      - title: '02 - Iron'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Iron Ingot'
                                const: 0
                              - title: '1 - Iron Block'
                                const: 1
                              - title: '2 - Iron Ore - Raw'
                                const: 2
                      - title: '03 - Gold'
                        bar_index:
                            const: 3
                        icon_index:
                            or:
                              - title: '0 - Gold Ingot'
                                const: 0
                              - title: '1 - Gold Block'
                                const: 1
                              - title: '2 - Gold Ore - Raw'
                                const: 2
                      - title: '04 - Lapis Lazuli'
                        bar_index:
                            const: 4
                        icon_index:
                            or:
                              - title: '0 - Lapis Lazuli'
                                const: 0
                              - title: '1 - Lapis Lazuli Block'
                                const: 1
                      - title: '05 - Redstone'
                        bar_index:
                            const: 5
                        icon_index:
                            or:
                              - title: '0 - Redstone Dust'
                                const: 0
                              - title: '1 - Redstone Block'
                                const: 1
                      - title: '06 - Coal'
                        bar_index:
                            const: 6
                        icon_index:
                            or:
                              - title: '0 - Coal'
                                const: 0
                              - title: '1 - Coal Block'
                                const: 1
                      - title: '07 - Diamond'
                        bar_index:
                            const: 7
                        icon_index:
                            or:
                              - title: '0 - Diamond'
                                const: 0
                              - title: '1 - Diamond Block'
                                const: 1
                      - title: '08 - Netherite'
                        bar_index:
                            const: 8
                        icon_index:
                            or:
                              - title: '0 - Netherite Ingot'
                                const: 0
                              - title: '1 - Netherite Block'
                                const: 1
                              - title: '2 - Netherite Scrap'
                                const: 2
                              - title: '3 - Ancient Debris'
                                const: 3
                      - title: '09 - Nether Quartz'
                        bar_index:
                            const: 9
                        icon_index:
                            or:
                              - title: '0 - Nether Quartz'
                                const: 0
                              - title: '1 - Nether Quartz Block'
                                const: 1
                      - title: '10 - Amethyst'
                        bar_index:
                            const: 10
                        icon_index:
                            or:
                              - title: '0 - Amethyst Shard'
                                const: 0
                              - title: '1 - Anethyst Block'
                                const: 1
                      - title: '11 - Wind Charge'
                        bar_index:
                            const: 11
                        icon_index:
                            or:
                              - title: '0 - Wind Charge'
                                const: 0
                              - title: '1 - Breeze'
                                const: 1
                              - title: '2 - Breeze Rod'
                                const: 2
                      - title: '12 - Shulker'
                        bar_index:
                            const: 12
                      - title: '13 - Spider'
                        bar_index:
                            const: 13
                        icon_index:
                            or:
                              - title: '0 - Spider'
                                const: 0
                              - title: '1 - Spider Eye'
                                const: 1
                              - title: '2 - Cave Spider'
                                const: 2
                      - title: '14 - Fish'
                        bar_index:
                            const: 14
                        icon_index:
                            or:
                              - title: '0 - Cod'
                                const: 0
                              - title: '1 - Salmon'
                                const: 1
                              - title: '2 - Tropical Fish'
                                const: 2
                              - title: '3 - Pufferfish'
                                const: 3
                      - title: '15 - Phantom'
                        bar_index:
                            const: 15
                        icon_index:
                            or:
                              - title: '0 - Phantom Body'
                                const: 0
                              - title: '1 - Phantom Head'
                                const: 1
                              - title: '2 - Phantom Membrane'
                                const: 3
                      - title: '16 - Nautilus'
                        bar_index:
                            const: 16
                        icon_index:
                            or:
                              - title: '0 - Nautilus Shell'
                                const: 0
                              - title: '1 - Nautilus'
                                const: 1
                              - title: '2 - Conduit'
                                const: 2
                      - title: '17 - Squid'
                        bar_index:
                            const: 17
                        icon_index:
                            or:
                              - title: '0 - Ink Sac'
                                const: 0
                              - title: '1 - Squid'
                                const: 1
                      - title: '18 - Glow Squid'
                        bar_index:
                            const: 18
                        icon_index:
                            or:
                              - title: '0 - Glow Ink Sac'
                                const: 0
                              - title: '1 - Glow Squid'
                                const: 1
                      - title: '19 - Sniffer'
                        bar_index:
                            const: 19
                        icon_index:
                            or:
                              - title: '0 - Sniffer'
                                const: 0
                              - title: '1 - Sniffer Egg'
                                const: 1
                      - title: '20 - Turtle Shell'
                        bar_index:
                            const: 20
                      - title: '21 - Armadillo'
                        bar_index:
                            const: 21
                        icon_index:
                            or:
                              - title: '0 - Armadillo Scute'
                                const: 0
                              - title: '1 - Armadillo'
                                const: 1
                              - title: '2 - Armadillo - Defense Curl'
                                const: 2
                      - title: '22 - Vines'
                        bar_index:
                            const: 22
                        icon_index:
                            or:
                              - title: '0 - Mossy Stone'
                                const: 0
                              - title: '1 - Vines'
                                const: 1
                      - title: '23 - Slime'
                        bar_index:
                            const: 23
                        icon_index:
                            or:
                              - title: '0 - Slime Block'
                                const: 0
                              - title: '1 - Slime'
                                const: 1
                              - title: '2 - Slimeball'
                                const: 2
                      - title: '24 - Magma Cube'
                        bar_index:
                            const: 24
                        icon_index:
                            or:
                              - title: '0 - Magma Block'
                                const: 0
                              - title: '1 - Magma Cube'
                                const: 1
                              - title: '2 - Magma Cream'
                                const: 2
                  - title: '02 - Effects and Blocks'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/vevehki/resource_bar_02.png"
                    or:
                      - title: '00 - TNT'
                        bar_index:
                            const: 0
                        icon_index:
                            or:
                              - title: '0 - TNT Block'
                                const: 0
                              - title: '1 - Dynamite'
                                const: 1
                      - title: '01 - Brick'
                        bar_index:
                            const: 1
                        icon_index:
                            or:
                              - title: '0 - Brick'
                                const: 0
                              - title: '1 - Bricks (Block)'
                                const: 1
                              - title: '2 - Furnace Fire'
                                const: 2
                      - title: '02 - Bed'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Bed'
                                const: 0
                              - title: '1 - Bed Item'
                                const: 1
                      - title: '03 - Target'
                        bar_index:
                            const: 3
                        icon_index:
                            or:
                              - title: '0 - Target Block'
                                const: 0
                              - title: '1 - Bow and Arrow'
                                const: 1
                      - title: '04 - Sculk Echo'
                        bar_index:
                            const: 4
                        icon_index:
                            or:
                              - title: '0 - Echo Shard'
                                const: 0
                              - title: '1 - Sculk Block'
                                const: 1
                              - title: '2 - Shrieker'
                                const: 2
                              - title: '3 - Sculk Sensor'
                                const: 3
                      - title: '05 - Grass Block'
                        bar_index:
                            const: 5
                        icon_index:
                            or:
                              - title: '0 - Grass Block'
                                const: 0
                              - title: '1 - Dirt Block'
                                const: 1
                      - title: '06 - Lava Bucket'
                        bar_index:
                            const: 6
                      - title: '07 - Bubble'
                        bar_index:
                            const: 7
                        icon_index:
                            or:
                              - title: '0 - Bubble - Large'
                                const: 0
                              - title: '1 - Bubbles'
                                const: 1
                      - title: '08 - Sonic Resonance'
                        bar_index:
                            const: 8
                      - title: '09 - Firework'
                        bar_index:
                            const: 9
                      - title: '10 - Hunger'
                        bar_index:
                            const: 10
                      - title: '11 - Honey'
                        bar_index:
                            const: 11
                        icon_index:
                            or:
                              - title: '0 - Honeycomb'
                                const: 0
                              - title: '1 - Honey Bottle'
                                const: 1
                      - title: '12 - Endermite'
                        bar_index:
                            const: 12
                      - title: '13 - Silverfish'
                        bar_index:
                            const: 13
                        icon_index:
                            or:
                              - title: '0 - Chiseled Stone'
                                const: 0
                              - title: '1 - Silverfish'
                                const: 1
                      - title: '14 - Rotten Flesh Zombie'
                        bar_index:
                            const: 14
                        icon_index:
                            or:
                              - title: '0 - Rotten Flesh'
                                const: 0
                              - title: '1 - Bone'
                                const: 1
                              - title: '2 - Zombie'
                                const: 2
                              - title: '3 - Husk'
                                const: 3
                              - title: '4 - Drowned'
                                const: 4
                      - title: '15 - Lucky Block'
                        bar_index:
                            const: 15
                        icon_index:
                            or:
                              - title: '0 - [?] Block'
                                const: 0
                              - title: '1 - [!] Block'
                                const: 1
                      - title: '16 - Crimson<->Warped Mushroom'
                        bar_index:
                            const: 16
                        icon_index:
                            or:
                              - title: '0 - Crimson Mushroom'
                                const: 0
                              - title: '1 - Warped Mushroom'
                                const: 1
                      - title: '17 - Beacon'
                        bar_index:
                            const: 17
                        icon_index:
                            or:
                              - title: '0 - Beacon'
                                const: 0
                              - title: '1 - Beacon Light'
                                const: 1
                      - title: '18 - Bread'
                        bar_index:
                            const: 18
                      - title: '19 - Bad Omen'
                        bar_index:
                            const: 19
                        icon_index:
                             or:
                              - title: '0 - Bad Omen'
                                const: 0
                              - title: '1 - Trial Omen'
                                const: 1
                              - title: '2 - Raid Omen'
                                const: 2
                      - title: '20 - Crafting Table'
                        bar_index:
                            const: 20
                        icon_index:
                            or:
                              - title: '0 - Crafting Table'
                                const: 0
                              - title: '1 - Crafter'
                                const: 1
                              - title: '2 - Smithing Table'
                                const: 2
                      - title: '21 - Furnace'
                        bar_index:
                            const: 21
                        icon_index:
                            or:
                              - title: '0 - Furnace'
                                const: 0
                              - title: '1 - Smoker'
                                const: 1
                              - title: '2 - Blast Furnace'
                                const: 2
                              - title: '3 - Furnace - Lit'
                                const: 3
                              - title: '4 - Smoker - Lit'
                                const: 4
                              - title: '5 - Blast Furnace - Lit'
                                const: 5
                      - title: '22 - Bookshelf'
                        bar_index:
                            const: 22
                        icon_index:
                            or:
                              - title: '0 - Bookshelf'
                                const: 0
                              - title: '1 - Book'
                                const: 1
                              - title: '2 - Enchanting Table'
                                const: 2
                              - title: '3 - Lectern'
                                const: 3
                      - title: '23 - Campfire'
                        bar_index:
                            const: 23
                        icon_index:
                            or:
                              - title: '0 - Campfire'
                                const: 0
                              - title: '1 - Soul Campfire'
                                const: 1
                              - title: '2 - Fire with Smoke'
                                const: 2
                      - title: '24 - Compass'
                        bar_index:
                            const: 24
                        icon_index:
                            or:
                              - title: '0 - Compass'
                                const: 0
                              - title: '1 - Treasure Map'
                                const: 1
                              - title: '2 - Cartography Table'
                                const: 2
                              - title: '3 - Lodestone'
                                const: 3
                  - title: '03 - Indicators'
                    sprite_location:
                        const: "origins:textures/gui/sprites/hud_render/vevehki/resource_bar_03.png"
                    or:
                      - title: '00 - Experience'
                        bar_index:
                            const: 0
                        icon_index:
                            or:
                              - title: '0 - Experience Orb - Large'
                                const: 0
                              - title: '1 - Experience Bottle'
                                const: 1
                      - title: '01 - Trial Chambers'
                        bar_index:
                            const: 1
                        icon_index:
                            or:
                              - title: '0 - Trial Key'
                                const: 0
                              - title: '1 - Ominous Trial Key'
                                const: 1
                              - title: '2 - Trial Spawner'
                                const: 2
                              - title: '3 - Ominous Trial Spawner'
                                const: 3
                              - title: '4 - Vault'
                                const: 4
                              - title: '5 - Ominous Vault'
                                const: 5
                      - title: '02 - Brewing Stand'
                        bar_index:
                            const: 2
                        icon_index:
                            or:
                              - title: '0 - Brewing Stand'
                                const: 0
                              - title: '1 - Cauldron'
                                const: 1
                              - title: '2 - Fire Potion'
                                const: 2
                      - title: '03 - Nebula Star'
                        bar_index:
                            const: 3
                        icon_index:
                            or:
                              - title: '0 - Nebula Orb'
                                const: 0
                              - title: '1 - 4-Point Star'
                                const: 1
                              - title: '2 - 5-Point Star'
                                const: 2
                      - title: '04 - Temperature'
                        bar_index:
                            const: 4
                      - title: '05 - Moon Phase'
                        bar_index:
                            const: 5
                        icon_index:
                            or:
                              - title: '0 - Full Moon'
                                const: 0
                              - title: '1 - Waning Gibbous'
                                const: 1
                              - title: '2 - Third Quarter'
                                const: 2
                              - title: '3 - Waning Crescent'
                                const: 3
                              - title: '4 - Full Moon'
                                const: 4
                              - title: '5 - Waxing Crescent'
                                const: 5
                              - title: '6 - First Quarter'
                                const: 6
                              - title: '7 - Waxing Gibbous'
                                const: 7
                      - title: '06 - Darkness'
                        bar_index:
                            const: 6
                        icon_index:
                            or:
                              - title: '0 - Shaded Light Ring'
                                const: 0
                              - title: '1 - Darkness Status Effect'
                                const: 1
                      - title: '07 - Yin Yang'
                        bar_index:
                            const: 7
                        icon_index:
                            or:
                              - title: '0 - Yin Yang'
                                const: 0
                              - title: '1 - Yang Yin'
                                const: 1
                      - title: '08 - Yang Yin'
                        bar_index:
                            const: 8
                        icon_index:
                            or:
                              - title: '0 - Yin Yang'
                                const: 0
                              - title: '1 - Yang Yin'
                                const: 1
                      - title: '09 - Attack Bar'
                        bar_index:
                            const: 9
                        icon_index:
                            or:
                              - title: '0 - Crosshair - Lit'
                                const: 0
                              - title: '1 - Crosshair - Unlit'
                                const: 1
                      - title: '10 - Rainbow'
                        bar_index:
                            const: 10
                      - title: '11 - Face'
                        bar_index:
                            const: 11
                        icon_index:
                            or:
                              - title: '0 - Asian'
                                const: 0
                              - title: '1 - White'
                                const: 1
                              - title: '2 - Hispanic'
                                const: 2
                              - title: '3 - Black'
                                const: 3
                      - title: '12 - Soul'
                        bar_index:
                            const: 12
                        icon_index:
                            or:
                              - title: '0 - Blue Soul'
                                const: 0
                              - title: '1 - Soul Sand'
                                const: 1
                      - title: '13 - Brush'
                        bar_index:
                            const: 13
                        icon_index:
                            or:
                              - title: '0 - Brush'
                                const: 0
                              - title: '1 - Suspicious Sand'
                                const: 1
                      - title: '14 - Lantern'
                        bar_index:
                            const: 14
                        icon_index:
                            or:
                              - title: '0 - Lantern'
                                const: 0
                              - title: '1 - Soul Lantern'
                                const: 1
                              - title: '2 - Torch'
                                const: 2
                              - title: '3 - Soul Torch'
                                const: 3
                      - title: '15 - Red Fist'
                        bar_index:
                            const: 15
                        icon_index:
                            or:
                              - title: '0 - Red Fist - Outlined'
                                const: 0
                              - title: '1 - Red Fist - No Outline'
                                const: 1
                      - title: '16 - Pizza'
                        bar_index:
                            const: 16
                        icon_index:
                            or:
                              - title: '0 - Pizza'
                                const: 0
                              - title: '1 - Pizza Slice'
                                const: 1
                      - title: '17 - Angry Eyes'
                        bar_index:
                            const: 17
                      - title: '18 - Sugar'
                        bar_index:
                            const: 18
                        icon_index:
                            or:
                              - title: '0 - Sugar'
                                const: 0
                              - title: '1 - Sugarcane'
                                const: 1
                      - title: '19 - Light'
                        bar_index:
                            const: 19
                        icon_index:
                            or:
                              - title: '0 - Lens Flare'
                                const: 0
                              - title: '1 - Angel Wings and Halo'
                                const: 1
                      - title: '20 - Rusting Iron'
                        bar_index:
                            const: 20
                        icon_index:
                            or:
                              - title: '0 - Rusting Iron Ingot'
                                const: 0
                              - title: '1 - Rusting Iron Block'
                                const: 1
                      - title: '21 - Pottery Sherd'
                        bar_index:
                            const: 21
                        icon_index:
                            or:
                              - title: '0 - Pottery Sherd'
                                const: 0
                              - title: '1 - Ancient Vase'
                                const: 1
                      - title: '22 - Glow Berries'
                        bar_index:
                            const: 22
                        icon_index:
                            or:
                              - title: '0 - Glow Berries'
                                const: 0
                              - title: '1 - Glow Berry Bush'
                                const: 1
                      - title: '23 - Creaking Resin'
                        bar_index:
                            const: 23
                        icon_index:
                            or:
                              - title: '0 - Creaking Resin'
                                const: 0
                              - title: '1 - Creaking Resin Brick'
                                const: 1
                              - title: '2 - The Creaking'
                                const: 2
                      - title: '24 - Prismatic Crystal'
                        bar_index:
                            const: 24
                        icon_index:
                            or:
                              - title: '0 - Prismatic Square'
                                const: 0
                              - title: '1 - Prismatic Triangle'
                                const: 1
          - title: custom
            sprite_location:
                desc: The path to the file in the assets which contains what the bar looks like.
                link: identifier
            bar_index:
                desc: The indexed position of the bar on the sprite to use.
                type: integer
                min: 0
                default: 0
            icon_index:
                desc: The indexed position of the icon on the sprite to use.
                type: integer
                min: 0
                default: 0
