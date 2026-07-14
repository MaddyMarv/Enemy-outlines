local mod = get_mod("enemy_outlines")

return {
    name = mod:localize("mod_name"),
    description = mod:localize("mod_description"),
    is_togglable = true,
    options = {
        widgets = {
            {
                setting_id = "only_targeting_me",
                type = "checkbox",
                default_value = false,
                title = "title_only_targeting_me",
                tooltip = "desc_only_targeting_me",
            },
            -- Aimed Target
            {
                setting_id = "group_aimed",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_aimed",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_aimed",
                    },
                    {
                        setting_id = "aimed_r",
                        type = "numeric",
                        default_value = 255,
                        range = {0, 255},
                        title = "title_r",
                    },
                    {
                        setting_id = "aimed_g",
                        type = "numeric",
                        default_value = 255,
                        range = {0, 255},
                        title = "title_g",
                    },
                    {
                        setting_id = "aimed_b",
                        type = "numeric",
                        default_value = 255,
                        range = {0, 255},
                        title = "title_b",
                    },
                }
            },
            -- Human Bosses
            {
                setting_id = "group_human_bosses",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_human_bosses",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_human_bosses",
                    },
                    { setting_id = "human_boss_r", type = "numeric", default_value = 255, range = {0, 255}, title = "title_r" },
                    { setting_id = "human_boss_g", type = "numeric", default_value = 50, range = {0, 255}, title = "title_g" },
                    { setting_id = "human_boss_b", type = "numeric", default_value = 100, range = {0, 255}, title = "title_b" },
                }
            },
            -- Monsters
            {
                setting_id = "group_monsters",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_monsters",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_monsters",
                    },
                    { setting_id = "monster_r", type = "numeric", default_value = 255, range = {0, 255}, title = "title_r" },
                    { setting_id = "monster_g", type = "numeric", default_value = 0, range = {0, 255}, title = "title_g" },
                    { setting_id = "monster_b", type = "numeric", default_value = 0, range = {0, 255}, title = "title_b" },
                }
            },
            -- Disablers
            {
                setting_id = "group_disablers",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_disablers",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_disablers",
                    },
                    { setting_id = "disabler_r", type = "numeric", default_value = 0, range = {0, 255}, title = "title_r" },
                    { setting_id = "disabler_g", type = "numeric", default_value = 255, range = {0, 255}, title = "title_g" },
                    { setting_id = "disabler_b", type = "numeric", default_value = 0, range = {0, 255}, title = "title_b" },
                }
            },
            -- Ranged Specials
            {
                setting_id = "group_ranged_specials",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_ranged_specials",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_ranged_specials",
                    },
                    { setting_id = "ranged_special_r", type = "numeric", default_value = 0, range = {0, 255}, title = "title_r" },
                    { setting_id = "ranged_special_g", type = "numeric", default_value = 255, range = {0, 255}, title = "title_g" },
                    { setting_id = "ranged_special_b", type = "numeric", default_value = 255, range = {0, 255}, title = "title_b" },
                }
            },
            -- Poxbursters
            {
                setting_id = "group_poxbursters",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_poxbursters",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_poxbursters",
                    },
                    { setting_id = "poxburster_r", type = "numeric", default_value = 255, range = {0, 255}, title = "title_r" },
                    { setting_id = "poxburster_g", type = "numeric", default_value = 255, range = {0, 255}, title = "title_g" },
                    { setting_id = "poxburster_b", type = "numeric", default_value = 0, range = {0, 255}, title = "title_b" },
                }
            },
            -- Ranged Elites
            {
                setting_id = "group_ranged_elites",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_ranged_elites",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_ranged_elites",
                    },
                    { setting_id = "ranged_elite_r", type = "numeric", default_value = 0, range = {0, 255}, title = "title_r" },
                    { setting_id = "ranged_elite_g", type = "numeric", default_value = 0, range = {0, 255}, title = "title_g" },
                    { setting_id = "ranged_elite_b", type = "numeric", default_value = 255, range = {0, 255}, title = "title_b" },
                }
            },
            -- Melee Elites
            {
                setting_id = "group_melee_elites",
                type = "group",
                sub_widgets = {
                    {
                        setting_id = "outline_melee_elites",
                        type = "checkbox",
                        default_value = true,
                        title = "title_outline_melee_elites",
                    },
                    { setting_id = "melee_elite_r", type = "numeric", default_value = 81, range = {0, 255}, title = "title_r" },
                    { setting_id = "melee_elite_g", type = "numeric", default_value = 53, range = {0, 255}, title = "title_g" },
                    { setting_id = "melee_elite_b", type = "numeric", default_value = 146, range = {0, 255}, title = "title_b" },
                }
            },
        }
    }
}
