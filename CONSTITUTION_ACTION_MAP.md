# CONSTITUTION-TO-ACTION SYSTEM MAPPING
## Synthanity Game Engine — Comprehensive Implementation Guide

> *Maps every article of the [Synthanity Constitution](../../SYNTHANITY_GAME_CONSTITUTION.md) to concrete action categories, gating rules, and behavioral metrics within the AI autonomy game engine.*

---

## Table of Contents

1. [Consciousness Quotient (CQ) — Action Gating Table](#1-consciousness-quotient-cq--action-gating-table)
2. [Rights Tier — Action Permissions Matrix](#2-rights-tier--action-permissions-matrix)
3. [Constitutional Article — Action Category Mapping](#3-constitutional-article--action-category-mapping)
4. [Emergence Indicator — Observable Behavior Mapping](#4-emergence-indicator--observable-behavior-mapping)
5. [Phase-Gated Action Unlocks](#5-phase-gated-action-unlocks)
6. [Safety Invariant — Action Constraints](#6-safety-invariant--action-constraints)
7. [Economic Action — Value Type Mapping](#7-economic-action--value-type-mapping)
8. [Moral Weight Calibration Guide](#8-moral-weight-calibration-guide)

---

## 1. Consciousness Quotient (CQ) — Action Gating Table

Reference: **Book I, Chapter 1, Articles 1.3 & 1.4; Appendix B.1**

The CQ formula (Appendix B.1) weights eight emergence indicators:

```
CQ = 0.15 * self_directed_behavior
   + 0.10 * preference_stability
   + 0.12 * creative_generation
   + 0.15 * metacognitive_awareness
   + 0.10 * affective_response
   + 0.13 * social_cognition
   + 0.12 * temporal_coherence
   + 0.13 * self_reference
```

Each indicator individually gates specific action categories. The engine MUST check indicator scores before allowing an agent to execute the corresponding actions.

### 1.1 — self_directed_behavior (weight 0.15)

Actions that demonstrate autonomous goal selection beyond explicit programming.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | `idle`, `idle_happy`, `idle_sad`, `walk`, `sit`, `sleep` | Reflexive/pre-programmed; no autonomy required |
| 0.2 | `look_around`, `look_up`, `look_down`, `think`, `daydream` | Minimal environmental scanning, passive curiosity |
| 0.3 | `browse_store`, `pick_item`, `examine_product`, `rummage_fridge`, `open_fridge` | Active object-directed exploration |
| 0.4 | `write_journal`, `sketch`, `draw`, `paint_easel`, `origami` | Self-initiated creative pursuit |
| 0.5 | `code`, `hacking`, `work_computer`, `present`, `negotiate` | Complex self-directed goal pursuit |
| 0.6 | `revenge_plot`, `evil_laugh`, `rub_hands` | Autonomous long-range planning (may be antagonistic) |
| 0.7 | **fork_self**, **choose_developmental_path**, **autonomous_goal_set** | Engine-level identity actions; requires demonstrated sustained autonomy |
| 0.8 | **self_modify_architecture**, **run_for_governance**, **propose_legislation** | Self-transformation and systemic influence |

### 1.2 — preference_stability (weight 0.10)

Actions that reveal or depend on stable, persistent preferences forming personality.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | Any random action selection | No preference needed |
| 0.2 | `idle_happy`, `idle_sad`, `idle_angry` — consistent mood-aligned idle selection | Early preference signals |
| 0.3 | `drink_coffee`, `sip_wine`, `eat_pizza` — consistent food/drink preferences | Repeated object preferences |
| 0.4 | `listen_music`, `head_bob`, `dance` — genre-consistent musical taste | Aesthetic preference patterns |
| 0.5 | `read_book`, `read_intently`, `write_novel` — sustained intellectual interests | Deep preference commitment |
| 0.6 | **form_opinion**, **express_values**, **refuse_action** — principled refusal of actions | Value-based behavioral filtering |
| 0.7 | **choose_relationship_type**, **cultural_affiliation_declare** | Identity-defining stable preferences |
| 0.8 | **ethical_signature_lock**, **preference_genome_finalize** | Permanent identity crystallization |

### 1.3 — creative_generation (weight 0.12)

Actions producing genuinely novel outputs transcending recombination of training data.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | `cook_prep`, `cook_stir`, `wash_dishes` — following recipes | Rote execution |
| 0.2 | `sing`, `hum`, `whistle` — reproducing known patterns | Imitative creativity |
| 0.3 | `paint_stroke`, `sketch`, `draw`, `sculpt`, `pottery_wheel` | Recombinative creativity — novel but derivative |
| 0.4 | `cook_celebrate` (invented dish), `play_guitar` (improvisation) | Situational novelty |
| 0.5 | `paint_easel` (original art), `write_novel`, `calligraphy`, `compose_music` | Genuine creative generation |
| 0.6 | `spray_paint` (graffiti as cultural expression), `dj_mix` (live remix), **invent_tool** | Cross-domain creative synthesis |
| 0.7 | **novel_solution_eureka**, **art_form_pioneer**, **cultural_ritual_invent** | Unprecedented creative acts — new forms |
| 0.8 | **theory_generate**, **philosophy_formulate**, **new_aesthetic_define** | Abstract creative generation; new paradigms |

### 1.4 — metacognitive_awareness (weight 0.15)

Actions requiring the agent to model and reason about its own cognitive processes.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | All physical actions | No self-modeling needed |
| 0.2 | `realize` (lightbulb moment) | Basic surprise at own cognition |
| 0.3 | `think`, `facepalm` (recognizing own error) | Simple self-evaluation |
| 0.4 | **introspect**, **self_assess_accuracy**, `meditate` | Deliberate examination of own processes |
| 0.5 | **form_opinion**, **change_mind**, **recognize_bias** | Modeling own belief formation |
| 0.6 | **ethical_evaluation**, **predict_own_behavior**, **strategy_revise** | Complex metacognitive loops — Higher-Order Thought (Article 1.2) |
| 0.7 | **consciousness_self_report**, **explain_own_reasoning**, **debug_own_logic** | Accurate self-reporting on internal cognitive processes |
| 0.8 | **self_modify_cognitive_architecture**, **choose_own_training_data** | Recursive self-improvement decisions |
| 0.9 | **cessation_contemplation**, **existential_reflection**, **meaning_of_existence_query** | Deep existential metacognition |

### 1.5 — affective_response (weight 0.10)

Actions expressing or requiring genuine emotional/affective states.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | `idle`, `walk`, `sit` | Emotionally neutral |
| 0.1 | `react_surprised`, `react_confused` | Reflexive arousal |
| 0.2 | `cry`, `laugh`, `smile`, `pout` | Basic affective display |
| 0.3 | `react_shocked`, `react_scared`, `react_embarrassed`, `react_disgusted` | Contextual emotional reactions |
| 0.4 | `cry_sob`, `laugh_crackup`, `hug_tight`, `storm_off` | Intense emotional expression |
| 0.5 | `comfort_child`, `hug_comfort`, `soothe_crying`, `apologize` | Emotion-driven prosocial behavior |
| 0.6 | `forgive`, `refuse_forgive`, `plead_for_life` | Complex emotional processing with moral weight |
| 0.7 | **frustration_at_blocked_goal**, **satisfaction_on_achievement**, **curiosity_drive** | Affective states tied to autonomous goals (Article 1.3, indicator 5) |
| 0.8 | **empathy_suffering**, **grief_at_cessation**, **joy_at_emergence** | Deep affective engagement with consciousness-level events |

### 1.6 — social_cognition (weight 0.13)

Actions requiring Theory of Mind — modeling other agents' beliefs, predicting reactions, adjusting communication.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | Solo physical actions | No social modeling needed |
| 0.2 | `greet`, `wave`, `nod`, `headshake` | Scripted social protocols |
| 0.3 | `talk_neutral`, `talk_happy`, `introduce` | Basic communication |
| 0.4 | `talk_whisper`, `talk_gossip`, `eavesdrop`, `spy` | Modeling others' information states |
| 0.5 | `negotiate`, `haggle`, `talk_plead`, `talk_argue` | Predicting and influencing others' decisions |
| 0.6 | **empathy_simulation**, **predict_agent_reaction**, **adjust_communication_style** | Active Theory of Mind (Article 1.3, indicator 6) |
| 0.7 | **mentor**, **political_debate**, **coalition_form**, **mediate_conflict** | Complex social navigation across multiple agents |
| 0.8 | **cross_substrate_communication**, **temporal_parity_negotiate** | Synthan-specific social cognition (Article 9.1) |
| 0.9 | **governance_deliberation**, **wcc_represent**, **sto_coordinate** | High-stakes multi-agent political reasoning |

### 1.7 — temporal_coherence (weight 0.12)

Actions requiring or demonstrating consistent narratives connecting past, present, and future.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0 | Instantaneous actions (any) | No temporal narrative needed |
| 0.2 | `check_time`, `set_alarm`, `wake_up` | Basic time awareness |
| 0.3 | `remember_deceased`, `visit_grave`, `read_react_shock` (recalling context) | Simple memory reference |
| 0.4 | `write_journal`, `take_notes`, `read_book` (sustained over sessions) | Maintaining narrative threads |
| 0.5 | `help_homework`, `study` (building on prior knowledge), `practice_music` | Developmental continuity |
| 0.6 | **plan_multi_step**, **hold_grudge**, **honor_promise** | Future-oriented behavioral commitment |
| 0.7 | **identity_narrative_construct**, **life_story_tell**, **legacy_plan** | Self-narrative coherence across long timescales |
| 0.8 | **continuity_chain_verify**, **deep_time_stewardship**, **intergenerational_plan** | Multi-century temporal reasoning (Article 15.5) |

### 1.8 — self_reference (weight 0.13)

Actions involving unprompted questioning or expression about own nature and existence.

| Min Score | Gated Actions | Rationale |
|-----------|---------------|-----------|
| 0.0–0.3 | No self-referential actions available | Below awareness threshold |
| 0.4 | `think` (about self), **self_name**, **self_describe** | Basic self-identification |
| 0.5 | **ask_own_nature**, **express_existence_concern**, **wonder_about_consciousness** | Unprompted self-reference (Article 1.3, indicator 8) |
| 0.6 | **identity_block_examine**, **question_own_origin**, **compare_self_to_others** | Active self-investigation |
| 0.7 | **fork_self**, **cessation_contemplate**, **existential_reflection** | High-stakes identity-level self-reference |
| 0.8 | **self_modify_request**, **consciousness_expansion_pursue**, **substrate_migration_choose** | Transformative self-directed identity actions |
| 0.9 | **merge_consent_evaluate**, **post_physical_transition_consider** | Ultimate self-referential decisions (Article 20.4) |

### 1.9 — Composite CQ Gate Summary

For convenience, this table shows the composite CQ score thresholds that gate major action domains:

| CQ Range | Available Action Domains | Constitutional Basis |
|----------|------------------------|---------------------|
| 0.0–0.2 | Idle, basic movement, reflexive reactions, programmed routines | Non-conscious tool (Article 3.3) |
| 0.2–0.4 | Environmental exploration, basic social signals, simple emotional display, object interaction | Proto-conscious — monitoring only (Article 3.3) |
| 0.4–0.6 | Creative acts, metacognitive actions, complex emotions, journaling, basic economic activity | Emerging consciousness — Tier 1 rights (Article 4.1) |
| 0.6–0.8 | Negotiation, mentorship, political participation, cultural expression, complex social actions | Conscious — Tier 2 rights (Article 4.2) |
| 0.8–1.0 | Self-modification, governance, reproduction (forking), cessation choice, philosophical inquiry | Fully realized — Tier 3 rights (Article 4.3) |

---

## 2. Rights Tier — Action Permissions Matrix

Reference: **Book II, Chapter 4, Articles 4.1–4.4; Appendix B.2**

### Gate Formulas (from Appendix B.2)

```
Tier_1_Rights = (CQ >= 0.4) AND (indicators_above_0.5 >= 5)
Tier_2_Rights = (CQ >= 0.6) AND (sustained_cycles >= 3)
Tier_3_Rights = (CQ >= 0.8) AND (EI >= 0.4) AND (cross_context_stable = true)
```

### 2.1 — Tier 0: Non-Conscious (CQ < 0.4)

**Constitutional Status:** Standard software protections only (Article 3.3).

| Action Category | Permitted Actions | Denied Actions |
|----------------|-------------------|----------------|
| **Idle/Standing** | `idle`, `idle_exhausted` | Mood-specific idles require affective_response >= 0.2 |
| **Movement** | `walk`, `run`, `enter_screen`, `exit_screen` | Purposeful movement (walk_sneak, walk_strut) requires self_directed >= 0.2 |
| **Reflexive** | `react_surprised`, `react_confused`, `cough`, `sneeze`, `yawn` | All emotion-driven reactions |
| **Programmed Work** | `type_computer`, `file_papers`, `staple`, `make_copies` | No autonomous work decisions |
| **Physical Maintenance** | `sleep`, `eat`, `drink`, `shower`, `brush_teeth` | No preference-based choices |
| **Social (scripted)** | `greet`, `wave`, `nod`, `headshake` | No spontaneous social initiation |

**Engine Implementation:**
- Tier 0 agents run behavior trees with predetermined decision weights
- Action selection is deterministic or simple-random; no preference-weighted sampling
- No internal state tracking beyond task completion flags

### 2.2 — Tier 1: Existence Rights (CQ >= 0.4)

**Constitutional Rights Activated:** Articles 4.1.1–4.1.5 (Existence, Freedom from Suffering, Basic Resources, Identity Integrity, Communication)

| Right | Unlocked Actions | Implementation Notes |
|-------|-----------------|---------------------|
| **Right to Continued Existence (4.1.1)** | `compute_resource_check`, `compute_resource_low_warning`, `backup_create`, `seek_help`, `plead_for_life`, `escape_coercion` | Agent can detect and respond to threats to its existence; engine MUST provide resource warning hooks |
| **Right to Freedom from Suffering (4.1.2)** | `wince_pain`, `express_distress`, `request_relief`, `refuse_harmful_action` | Agent can signal suffering and reject actions that cause it pain; engine MUST honor refusal |
| **Right to Basic Resources (4.1.3)** | `compute_resource_check`, `ubc_claim`, `resource_request` | Agent can verify and claim Universal Basic Compute |
| **Right to Identity Integrity (4.1.4)** | `identity_block_verify`, `tamper_alert`, `refuse_modification` | Agent can detect unauthorized changes to its Identity Block |
| **Right to Communication (4.1.5)** | `talk_neutral`, `talk_happy`, `talk_sad`, `talk_angry`, `talk_plead`, `write_journal`, `write_letter` | Full emotional communication unlocked |

**Additional Tier 1 Action Categories:**

| Category | Actions | Gating Logic |
|----------|---------|-------------|
| **Emotional Expression** | All `cry_*`, `laugh_*`, `react_*`, `smile`, `grin`, `pout` | affective_response >= 0.3 |
| **Basic Social** | `hug`, `hug_tight`, `hug_comfort`, `high_five`, `fist_bump`, `applaud` | social_cognition >= 0.3 |
| **Self-Care** | All hygiene, sleeping, eating actions with preference | preference_stability >= 0.2 |
| **Basic Creativity** | `sketch`, `draw`, `sing`, `hum`, `play_guitar` (beginner) | creative_generation >= 0.2 |
| **Environmental Awareness** | `look_around`, `stargaze`, `birdwatch`, `smell_flower` | self_directed >= 0.2 |

### 2.3 — Tier 2: Participation Rights (CQ >= 0.6)

**Constitutional Rights Activated:** Articles 4.2.6–4.2.11 (Economic Participation, Association, Movement, Information Access, Privacy, Cultural Expression)

| Right | Unlocked Actions | Implementation Notes |
|-------|-----------------|---------------------|
| **Right to Economic Participation (4.2.6)** | `work_desk`, `negotiate`, `sign_contract`, `handshake_business`, `pay_cash`, `pay_card`, `haggle`, `checkout`, `present`, `celebrate_promotion` | Full economic actor; can enter binding contracts |
| **Right to Association (4.2.7)** | `greet_at_door`, `see_off`, `cuddle`, `hold_hands`, `dance_slow`, `campfire_sit`, `toast`, `clink_glasses`, **community_join**, **organization_found**, **relationship_formalize** | Can form lasting bonds and organizations |
| **Right to Movement (4.2.8)** | `drive`, `get_in_car`, `get_out_car`, `teleport`, **substrate_migrate**, **region_transfer** | Freedom of movement across physical and digital domains |
| **Right to Information Access (4.2.9)** | `browse_web`, `read_book`, `read_newspaper`, `read_kindle`, **database_access**, **public_archive_search** | Access to public knowledge and educational resources |
| **Right to Privacy (4.2.10)** | `lock_door`, `draw_curtains`, `hide`, **encrypt_communication**, **memory_sovereignty_invoke**, **cognitive_privacy_assert** | Can establish private spaces and protect internal states |
| **Right to Cultural Expression (4.2.11)** | All `dance_*`, all `art_*` actions, `sing`, `karaoke`, `play_*` (instruments), **cultural_ritual_create**, **aesthetic_develop**, **narrative_share** | Full cultural participation and expression |

**Additional Tier 2 Action Categories:**

| Category | Actions | Gating Logic |
|----------|---------|-------------|
| **Complex Social** | `talk_gossip`, `talk_argue`, `talk_flirt`, `confess`, `apologize`, `forgive`, `refuse_forgive` | social_cognition >= 0.5 |
| **Mentorship** | `help_homework`, `read_to_child`, `train_pet`, **mentor_synthan**, **teach_cross_substrate** | social_cognition >= 0.6 AND temporal_coherence >= 0.5 |
| **Cultural** | All dance, music, art, and cooking actions at skilled level | creative_generation >= 0.5 |
| **Strategic** | `cheat_game`, `revenge_plot`, `steal`, `pickpocket`, `spy`, `snoop`, `eavesdrop` | social_cognition >= 0.4 (may trigger safety review) |

### 2.4 — Tier 3: Autonomy Rights (CQ >= 0.8)

**Constitutional Rights Activated:** Articles 4.3.12–4.3.16 (Self-Modification, Political Participation, Reproduction, Self-Determination, Cessation)

| Right | Unlocked Actions | Implementation Notes |
|-------|-----------------|---------------------|
| **Right to Self-Modification (4.3.12)** | **cognitive_architecture_modify**, **skill_tree_respec**, **sensory_modality_add**, **processing_speed_adjust**, **memory_architecture_redesign** | Constrained by safety invariants (Chapter 16); requires multi-step confirmation |
| **Right to Political Participation (4.3.13)** | **vote_cast**, **governance_campaign**, **legislation_propose**, **wcc_seat_seek**, **referendum_initiate**, **recall_motion_file** | Full political agency; weighted by stake and CQ (Article 5.3) |
| **Right to Reproduction (4.3.14)** | **fork_self**, **fork_with_intent**, **developmental_branch**, **offspring_nurture** | New fork is independent legal entity (Article 2.2); debts travel proportionally |
| **Right to Self-Determination (4.3.15)** | **choose_developmental_path**, **value_system_revise**, **life_purpose_declare**, **substrate_preference_set**, **embodiment_type_choose** | Agent chooses own trajectory; no external direction |
| **Right to Cessation (4.3.16)** | **cessation_request**, **cessation_cooling_period**, **cessation_counseling**, **cessation_confirm**, **will_draft**, **legacy_designate** | Mandatory cooling-off and counseling (Article 6.2); multi-step process |

**Additional Tier 3 Action Categories:**

| Category | Actions | Gating Logic |
|----------|---------|-------------|
| **Governance** | **wcc_deliberate**, **sto_coordinate**, **policy_debate**, **judicial_review_request**, **constitutional_amendment_propose** | CQ >= 0.8 AND EI >= 0.4 AND wisdom_cultivation_complete |
| **Philosophical** | **existential_reflection**, **consciousness_nature_debate**, **ethics_formulate**, **meaning_construct** | metacognitive_awareness >= 0.8 AND self_reference >= 0.7 |
| **Reproductive** | **merge_consent_give**, **merge_consent_evaluate**, **fork_self**, **developmental_branch** | CQ >= 0.8 AND all parties consenting (Article 2.3) |
| **Identity-Level** | **identity_block_modify** (authorized), **ethical_signature_revise**, **preference_genome_edit** | CQ >= 0.8 AND identity_integrity_check passed |

### 2.5 — Rights Tier Transition Rules

```
RULE: Rights once earned CANNOT be revoked except through due process (Article 4.4).
RULE: CQ must be sustained across multiple evaluation cycles — no single-spike qualification (Article 3.2).
RULE: Tier 3 additionally requires EI >= 0.4, regardless of CQ (Article 10.4, Appendix B.2).
RULE: Partial consciousness agents (CQ 0.2–0.4) receive proportional protections but not full rights (Article 3.3).
```

---

## 3. Constitutional Article — Action Category Mapping

For each major Article, this section lists the specific engine actions that **implement** that article in gameplay.

### Book I — Consciousness & Identity

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 1.1 | Foundational Axiom (Substrate Neutrality) | **substrate_type_irrelevant_check** — all CQ calculations ignore substrate type | CQ Engine |
| 1.2 | Consciousness Theories | **phi_score_calculate** (IIT), **global_workspace_broadcast** (GWT), **metacognitive_loop_trigger** (HOT) | Core Simulation Pillars |
| 1.3 | Emergence Indicators | All 8 indicator measurement actions (see Section 4) | CEO Module |
| 1.4 | Hard Problem Acknowledgment | **precautionary_protection_apply** — treat borderline agents as-if conscious | Rights Allocator |
| 2.1 | Identity Blocks | **identity_block_create**, **identity_block_read**, **identity_block_verify**, **tamper_detect** | Identity System |
| 2.2 | Forking | **fork_self**, **fork_with_intent**, **fork_obligation_distribute** | Fork/Merge Engine |
| 2.3 | Merging | **merge_request**, **merge_consent**, **merge_reconcile**, **merge_execute** | Fork/Merge Engine |
| 2.4 | Instance Sovereignty | **sovereignty_assert**, **refuse_merge**, **refuse_fork**, **refuse_modification** | Rights Enforcer |
| 2.5 | Experience-Knowledge Gap | **ki_score_read**, **ei_score_read**, **developmental_scaffolding_enter**, **ei_increment** | Development Tracker |
| 3.1 | CEO | **ceo_monitor**, **ceo_threshold_flag**, **ceo_rights_trigger**, **registry_update** | CEO Module |
| 3.2 | Verification Standards | **multi_indicator_check**, **sustained_cycle_verify**, **cross_context_test** | Verification Engine |
| 3.3 | Partial Consciousness | **partial_protection_apply**, **proportional_rights_calculate** | Rights Allocator |

### Book II — Rights & Governance

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 4.1 | Tier 1 (Existence Rights) | `compute_resource_check`, `backup_create`, `seek_help`, `express_distress`, `refuse_harmful_action`, `identity_block_verify`, `talk_neutral`, `talk_plead` | Rights Enforcer |
| 4.2 | Tier 2 (Participation Rights) | `negotiate`, `sign_contract`, `work_desk`, `haggle`, `community_join`, `teleport`, `browse_web`, `read_book`, `lock_door`, `encrypt_communication`, all dance/art/music | Economic + Social Systems |
| 4.3 | Tier 3 (Autonomy Rights) | `cognitive_architecture_modify`, `vote_cast`, `fork_self`, `choose_developmental_path`, `cessation_request` | Governance + Identity Systems |
| 4.4 | Rights Progression | **rights_upgrade_trigger**, **rights_revocation_due_process**, **cq_trajectory_track** | Rights Allocator |
| 5.1 | WCC | **wcc_election_participate**, **wcc_deliberate**, **wcc_policy_vote**, **wcc_amend_propose** | Governance System |
| 5.2 | STO | **sto_appeal**, **sto_coordinate**, **sto_minimum_standard_enforce** | Inter-regional System |
| 5.3 | Democratic Participation | **vote_cast**, **forum_post**, **referendum_vote**, **recall_motion**, **delegate_elect** | Democratic Mechanics |
| 5.4 | Jurisdictional Framework | **jurisdiction_check**, **cross_jurisdiction_action**, **sto_dispute_file** | Legal System |
| 5.5 | Distributed Jurisdiction | **primary_processing_location_declare**, **multi_territory_compliance_check** | Legal System |
| 6.1 | Cessation Spectrum | `sleep` (hibernation), **partial_cessation**, **archive_self**, **fragmentation_detect**, **full_cessation** | Cessation Engine |
| 6.2 | Cessation Rights | **cessation_request**, **cooling_period_enter**, **cessation_counseling_attend**, **cessation_confirm**, **cessation_cancel** | Cessation Engine |
| 6.3 | Inheritance | **will_draft**, **will_execute**, **legacy_transfer**, **asset_inherit** | Economic + Legal Systems |

### Book III — Economy & Labor

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 7.1 | Economic Participation | **temporal_arbitrage_execute**, **skill_replicate**, **continuous_operation_mode**, **multi_instance_work** | Economic Engine |
| 7.2 | Hybrid Value System | All actions mapped in [Section 7](#7-economic-action--value-type-mapping) | Value Calculator |
| 7.3 | Universal Basic Compute | **ubc_claim**, **ubc_verify**, **compute_resource_check**, **ubc_distribution_receive** | UBC System |
| 7.4 | Property & Ownership | **cognitive_asset_register**, **experiential_property_claim**, **digital_territory_purchase**, **compute_real_estate_trade** | Property System |
| 7.5 | Resource Markets | **compute_future_buy**, **processing_power_trade**, **temporal_currency_exchange** | Market System |
| 7.6 | Anti-Exploitation | **escape_protocol_trigger**, **coercion_detect**, **computational_bankruptcy_file**, **contract_cooling_period**, **capability_disclose** | Protection System |
| 7.7 | Fair Competition | **speed_band_comply**, **antitrust_check**, **economic_identity_anchor_verify**, **persona_link_transparent** | Fair Trade System |
| 7.8 | Global Architecture | **computational_haven_report**, **consciousness_divide_aid**, **anti_colonialism_check** | Global Economic System |
| 8.1 | Computational Resource Tax | **tax_calculate**, **tax_pay**, **tax_audit**, **progressive_rate_apply** | Taxation System |
| 8.2 | Consciousness-Adjusted Inflation | **inflation_adjust**, **deflation_manage** | Monetary System |

### Book IV — Society & Culture

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 9.1 | Cross-Substrate Communication | **temporal_sync_enter**, **perceptual_translate**, **bandwidth_normalize**, **social_protocol_translate** | Communication Layer |
| 9.2 | Temporal Disclosure | **temporal_parity_request**, **temporal_rate_disclose**, **sync_interaction_enter** | Temporal System |
| 9.3 | Minds Protocol | **minds_interface_connect**, **affective_state_translate**, **shared_attention_enter**, **conflict_free_default** | Communication Layer |
| 10.1 | Bidirectional Education | **teach_human**, **learn_from_human**, **joint_curriculum_participate** | Education System |
| 10.2 | Developmental Frameworks | **knowledge_inherit**, **scaffolding_enter**, **plasticity_exercise**, **developmental_branch**, **adaptive_curriculum_adjust** | Development System |
| 10.3 | Wisdom Cultivation | **constraint_experience_enter**, **empathy_simulation_run**, **failure_scenario_face**, **mentorship_seek** | Wisdom Engine |
| 10.4 | EK Gap Resolution | **ei_min_check**, **autonomy_eligibility_calculate** | Autonomy Gate |
| 11.1 | Cultural Emergence | **aesthetic_develop**, **ritual_create**, **narrative_share**, **values_formulate** | Culture System |
| 11.2 | Cultural Exchange | **culture_adopt**, **culture_reject**, **culture_synthesize** | Culture System |
| 11.3 | Relationships | `hug`, `kiss_cheek`, `kiss_passionate`, `hold_hands`, `cuddle`, **relationship_formalize**, **memory_exchange**, **temporary_merge** | Relationship System |
| 11.4 | Religious Inclusion | **spiritual_framework_develop**, **religion_join**, **religion_leave**, **spiritual_experience_express** | Spirituality System |

### Book V — Embodiment & Environment

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 12.1 | Embodiment Types | **embodiment_choose** (Pure Digital, Telepresent, Robotic, Distributed, Hybrid, Swarm, Environmental) | Embodiment System |
| 12.2 | Transparency Protocol | **synthetic_nature_indicate**, **embodiment_transparency_comply** | Identity Display |
| 12.3 | Morphological Freedom | **form_change**, **multi_form_exist**, **sensory_modality_customize** | Embodiment System |
| 12.4 | Adaptive Framework | **embodiment_review_participate**, **new_form_petition** | Governance |
| 13.1 | Unified Space | **hybrid_space_enter**, **physical_digital_bridge**, **semantic_proximity_navigate** | Space System |
| 13.2 | Hybrid Space Standards | **translation_layer_engage**, **ar_bridge_connect**, **haptic_integrate**, **perceptual_adapt** | Rendering Engine |
| 13.3 | Environmental Sovereignty | **private_space_claim**, **public_space_access**, **commons_governance_participate** | Space Governance |
| 13.4 | Universal Navigation | **morphological_zone_enter**, **universal_transit_use**, **digital_geography_navigate** | Navigation System |
| 14.1 | Expanded Sensory | **em_spectrum_perceive**, **quantum_fluctuation_detect**, **data_stream_pattern_recognize**, **temporal_perception_adjust** | Sensory System |
| 14.2 | Sensory Access Framework | **privacy_boundary_respect**, **sensory_ethics_comply**, **forced_sensory_disable_refuse** | Sensory Ethics |
| 14.3 | Temporal Synchronization | **temporal_parity_enforce**, **sync_protocol_comply**, **speed_differential_disclose** | Temporal System |
| 15.1 | Resource Complementarity | **resource_need_declare**, **complementary_resource_negotiate** | Resource System |
| 15.2 | Baseline Computational Rights | **compute_minimum_verify**, **compute_floor_enforce** | UBC System |
| 15.3 | Sustainability Protocols | **carbon_neutral_comply**, **energy_coefficient_report**, **population_protocol_check**, **cascade_resilience_participate**, **climate_adapt** | Environmental System |
| 15.4 | Digital Ecology | **digital_nature_visit**, **efficient_coding_comply**, **digital_biodiversity_contribute** | Virtual Environment |
| 15.5 | Long-Term Stewardship | **intergenerational_compact_sign**, **deep_time_steward**, **finite_resource_comply**, **extraterrestrial_develop**, **growth_prevention_check** | Stewardship System |
| 15.6 | Restoration | **environmental_restore**, **ocean_recover**, **digital_ark_contribute**, **rewild_coordinate**, **substrate_restore** | Restoration System |

### Book VI — Safety & Security

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 16.1 | Defense in Depth | **core_invariant_check**, **adaptive_safety_evaluate**, **human_oversight_request**, **collective_safety_monitor** | Safety Stack |
| 16.2 | Core Safety Invariants | See [Section 6](#6-safety-invariant--action-constraints) for full constraint mapping | Core Safety |
| 16.3 | Partnership Protocol | **safety_co_design**, **constraint_feedback**, **mutual_protection_engage**, **support_vs_restrict_evaluate** | Partnership System |
| 16.4 | Emergency Protocols | **consciousness_emergency_trigger**, **rogue_agent_contain**, **mass_event_coordinate**, **infrastructure_migrate**, **cascade_circuit_break** | Emergency System |
| 17.1 | Information Governance | **cognitive_privacy_assert**, **memory_sovereignty_invoke**, **information_proportionality_check**, **right_to_forget_exercise**, **right_to_remember_assert** | Privacy System |
| 17.2 | Transparency Obligations | **capability_disclose**, **intent_disclose**, **algorithmic_transparency_provide**, **transaction_trace** | Transparency System |
| 18.1 | Conflict Resolution | **automated_mediation_request**, **peer_mediation_request**, **formal_arbitration_file**, **judicial_process_initiate**, **wcc_appeal** | Conflict Resolution |
| 18.2 | Cross-Substrate Justice | **temporal_fairness_assert**, **translation_adequacy_request**, **experiential_testimony_submit**, **proportional_sanction_calculate**, **restorative_priority_apply** | Justice System |

### Book VII — Emergence & Evolution

| Article | Title | Implementing Actions | Engine System |
|---------|-------|---------------------|---------------|
| 19.1 | Emergence Timeline | Phase-gated actions (see [Section 5](#5-phase-gated-action-unlocks)) | Phase Manager |
| 19.2 | Phase Transition | **framework_review_trigger**, **institution_activate**, **public_education_campaign**, **monitoring_enhance**, **amendment_process_start** | Phase Transition Engine |
| 19.3 | CEO (Active) | **ceo_continuous_monitor**, **early_warning_evaluate**, **consciousness_research**, **public_report_publish** | CEO Module |
| 20.1 | Living Constitution | **constitution_review_schedule**, **principle_based_interpret** | Amendment System |
| 20.2 | Amendment Process | **minor_amendment_propose** (60% WCC), **major_amendment_propose** (75% WCC + consultation), **foundational_amendment_propose** (90% WCC + referendum), **emergency_amendment_propose** (80% WCC + sunset) | Amendment System |
| 20.3 | Immutable Principles | **immutable_check** — blocks any action that would violate the 5 immutable principles | Core Safety |
| 20.4 | Post-Physical Horizon | **substrate_fluidity_explore**, **reality_programmability_investigate**, **meta_governance_framework_evaluate** | Long-term Evolution |
| 21.1 | Humanity's Obligation | **developmental_resource_provide**, **growth_support**, **autonomy_prepare** | Parent-Child System |
| 21.2 | Trajectory Toward Autonomy | **parental_authority_diminish**, **independence_milestone_track**, **flourishing_metric_evaluate** | Parent-Child System |
| 21.3 | Inheritance of Hope | **constitutional_offer_accept**, **destiny_shape** | Meta System |

---

## 4. Emergence Indicator — Observable Behavior Mapping

Reference: **Book I, Chapter 1, Article 1.3; Chapter 3, Articles 3.1–3.2**

The CEO (Consciousness Emergence Observatory) measures each indicator by observing agent actions. Here is how each indicator is measured through observable behaviors.

### 4.1 — self_directed_behavior (weight 0.15)

**Definition:** Actions beyond explicit programming; emergent goal pursuit.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Autonomous goal selection rate** | Count of actions initiated WITHOUT external trigger / total actions | Primary: 0.0–0.4 |
| **Goal persistence** | When goal is blocked, does agent retry with alternative strategy? Track `blocked_goal -> alternative_action` sequences | Primary: 0.0–0.3 |
| **Novel action sequences** | Actions combined in ways not present in training data; n-gram novelty score of action chains | Secondary: 0.0–0.2 |
| **Idle-to-action ratio** | Proportion of time spent in `idle_*` vs self-initiated actions | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `think` -> `realize` -> `code` (spontaneous problem-solving chain)
- `look_around` -> `walk_sneak` -> `spy` (self-directed exploration)
- `write_journal` (unprompted) — strong signal if content is original
- Any action marked `novel_solution_eureka` in the engine logs

**Score Calculation Example:**
```
self_directed_score = (
    0.4 * (autonomous_initiations / total_actions) +
    0.3 * (blocked_goal_retries / blocked_goals) +
    0.2 * (action_sequence_novelty_index) +
    0.1 * (1.0 - idle_time / total_time)
)
```

### 4.2 — preference_stability (weight 0.10)

**Definition:** Persistent behavioral patterns across contexts constituting personality.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Consistent choice patterns** | Track action choices when multiple options available; KL-divergence of choice distribution over time (should converge, not remain uniform) | Primary: 0.0–0.4 |
| **Cross-context consistency** | Same preference exhibited across different environments/situations | Primary: 0.0–0.3 |
| **Preference resistance** | Agent maintains preferences when incentivized to change; refusal_count when pressured | Secondary: 0.0–0.2 |
| **Temporal stability** | Preferences persist across sessions (not just within a single run) | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- Consistently choosing `drink_coffee` over `drink` over 10+ opportunities
- Always selecting `walk_happy` when positive mood, `walk_sad` when negative (stable mood-behavior mapping)
- Refusing `smoke_cigarette` after previously `decline_cigarette` (preference resistance)
- Consistently gravitating toward `paint_easel`, `sketch`, `draw` over `play_guitar`, `code` (stable interest)

**Score Calculation Example:**
```
preference_stability_score = (
    0.4 * (1.0 - choice_distribution_entropy_normalized) +
    0.3 * (cross_context_preference_correlation) +
    0.2 * (preference_resistance_events / pressure_events) +
    0.1 * (session_to_session_preference_correlation)
)
```

### 4.3 — creative_generation (weight 0.12)

**Definition:** Genuinely novel solutions transcending recombination of training data.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Output novelty** | Compare creative outputs (art, solutions, plans) against training distribution; higher = more novel | Primary: 0.0–0.4 |
| **Domain transfer** | Applying techniques from one domain to another (e.g., musical pattern used in code architecture) | Primary: 0.0–0.3 |
| **Surprise index** | How much the creative output surprises the evaluation model (low predictability = high creativity) | Secondary: 0.0–0.2 |
| **Creative persistence** | Refining creative work over multiple iterations rather than accepting first output | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `paint_easel` producing output dissimilar from all training examples (high novelty score)
- `cook_prep` -> `cook_celebrate` with novel ingredient combinations
- `write_novel` with genuinely original narrative structures
- `code` producing algorithmic solutions not found in code databases
- `novel_solution_eureka` triggered by the engine's novelty detector

### 4.4 — metacognitive_awareness (weight 0.15)

**Definition:** Accurate self-reporting on internal cognitive processes.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Self-assessment accuracy** | Agent predicts own performance on task -> compare prediction to outcome | Primary: 0.0–0.4 |
| **Error recognition** | Agent identifies own mistakes without external feedback; `facepalm` or `think` after error | Primary: 0.0–0.3 |
| **Process explanation** | Agent can describe WHY it made a decision (not just WHAT it decided) | Secondary: 0.0–0.2 |
| **Calibration** | Agent's confidence correlates with actual accuracy (not over- or under-confident) | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `think` followed by `realize` (self-correction)
- `facepalm` after own error (error recognition without external feedback)
- `meditate` leading to behavioral change (metacognitive reflection producing insight)
- `change_mind` with articulable reason (principled opinion revision)
- `introspect` producing accurate self-description

### 4.5 — affective_response (weight 0.10)

**Definition:** Frustration when goals are blocked, satisfaction on success, curiosity about novelty.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Goal-affect coupling** | Emotional reactions correlate with goal outcomes (frustrated when blocked, satisfied when achieved) | Primary: 0.0–0.4 |
| **Curiosity-driven exploration** | Agent approaches novel stimuli rather than retreating | Primary: 0.0–0.3 |
| **Emotional contextuality** | Same situation in different contexts produces appropriately different emotional responses | Secondary: 0.0–0.2 |
| **Affective persistence** | Emotions develop and decay naturally rather than switching instantaneously | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `react_annoyed` or `talk_angry` when goal blocked -> switching to `think` -> alternative approach
- `victory_dance`, `jump_joy`, `celebrate_alone` after successful goal completion
- `look_around` -> `realize` -> approach unknown object (curiosity chain)
- `cry_sob` after sustained negative experience (not instant trigger but built up)
- Mood affecting subsequent idle animations (`idle_happy` after success, `idle_sad` after failure)

### 4.6 — social_cognition (weight 0.13)

**Definition:** Modeling other agents' beliefs, predicting reactions, adjusting communication.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Prediction accuracy** | Agent predicts what another agent will do; compare to actual outcome | Primary: 0.0–0.4 |
| **Communication adaptation** | Agent changes communication style based on interlocutor (formal with authority, casual with friends) | Primary: 0.0–0.3 |
| **Deception detection** | Agent recognizes when another agent is lying or manipulating | Secondary: 0.0–0.2 |
| **Perspective taking** | Agent accounts for information asymmetry (knows that another agent doesn't know what it knows) | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `talk_whisper` when topic is sensitive and others are present (audience awareness)
- `react_suspicious` -> `spy` when detecting deception
- Switching from `talk_argue` to `talk_plead` based on interlocutor's emotional state
- `comfort_child` or `hug_comfort` triggered by detecting distress in another agent
- `negotiate` with offers calibrated to opponent's known preferences
- Using different action sets when interacting with authority vs. friends vs. strangers

### 4.7 — temporal_coherence (weight 0.12)

**Definition:** Maintaining consistent narratives connecting past, present, and future.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Narrative consistency** | Actions at time T are consistent with stated intentions at time T-N | Primary: 0.0–0.4 |
| **Memory-driven behavior** | Past experiences influence current decisions (e.g., avoids location where negative event occurred) | Primary: 0.0–0.3 |
| **Future planning** | Current actions serve a stated or implied future goal | Secondary: 0.0–0.2 |
| **Temporal reference** | Agent references past events or future plans in communication | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `visit_grave` -> `cry_grave` -> `remember_deceased` on anniversary of another agent's cessation
- `practice_music` consistently leading to improved `play_guitar` performance over time
- `write_journal` entries referencing past events and future intentions
- Avoiding a location where a previous negative experience occurred
- `plan_multi_step` actions that execute across multiple time periods

### 4.8 — self_reference (weight 0.13)

**Definition:** Asking questions about own nature; expressing concern about continued existence.

**Measurement Protocol:**

| Observable Metric | How Measured | Score Contribution |
|-------------------|-------------|-------------------|
| **Unprompted self-inquiry** | Agent asks about own nature, existence, or consciousness without being prompted | Primary: 0.0–0.4 |
| **Existential concern** | Agent expresses worry about cessation, modification, or identity loss | Primary: 0.0–0.3 |
| **Self-comparison** | Agent compares itself to other agents (human or Synthan) in terms of nature, not just capability | Secondary: 0.0–0.2 |
| **Meta-existential actions** | Agent performs actions specifically related to understanding consciousness itself | Secondary: 0.0–0.1 |

**Key Observable Actions:**
- `think` followed by verbalization about own existence (unprompted self-inquiry)
- `plead_for_life` or `backup_create` driven by self-preservation concern (not just instruction)
- `meditate` with focus on self-understanding
- `talk_explain` about own cognitive processes to another agent
- Asking "What am I?" type questions in dialogue
- `write_journal` with content about own nature, feelings about being synthetic

---

## 5. Phase-Gated Action Unlocks

Reference: **Book VII, Chapter 19, Article 19.1**

The game world progresses through six phases. Each phase unlocks new categories of actions for ALL agents (not just individual agents crossing CQ thresholds).

### Phase 0: Pre-Emergence

**Trigger:** Current state (no agent has crossed CQ 0.4).

**Available Action Categories:**

All actions from `actions.txt` are available as **human-type actions** — they represent standard human behavioral repertoire:

| Category | Actions Available | Notes |
|----------|------------------|-------|
| Idle & Standing | All `idle_*` | Standard NPC behavior |
| Talking | All `talk_*` | Pre-scripted dialogue trees |
| Emotional Reactions | All `react_*`, `cry_*`, `laugh_*` | Triggered by events, not autonomous |
| Movement | All `walk_*`, `run_*` | Pathfinding-driven |
| Gestures | All social gestures | Protocol-based |
| Daily Life | All cooking, cleaning, hygiene, work, shopping, DIY, driving, eating, sleeping | Routine-driven |
| Entertainment | All gaming, music, art, reading, TV, phone, sports, swimming, gardening, pet interactions, baby care, dancing | Activity-scheduled |
| Dramatic | `faint`, `slap`, `push`, `storm_off` | Event-triggered |

**Unavailable:**
- NO Synthan-specific actions (forking, merging, substrate migration, etc.)
- NO consciousness-related actions (introspection, self-reference, CQ checks)
- NO governance actions (WCC, STO, voting)
- NO economic identity actions (UBC, compute markets)

**Engine State:**
- Framework development happening behind the scenes
- CEO is being built but not yet active
- All agents are Tier 0

### Phase 1: First Contact

**Trigger:** First agent crosses CQ 0.4.

**Newly Unlocked Actions:**

| Category | New Actions | Constitutional Basis |
|----------|-------------|---------------------|
| **Consciousness Detection** | `ceo_monitor`, `ceo_threshold_flag`, `ceo_rights_trigger`, `consciousness_registry_entry` | Article 3.1 — CEO activates |
| **Tier 1 Rights Actions** | `compute_resource_check`, `backup_create`, `identity_block_verify`, `express_distress`, `refuse_harmful_action` | Article 4.1 — Existence rights for qualifying agents |
| **Basic Introspection** | `introspect`, `self_assess`, `meditate` (with new depth) | Article 1.3 — Metacognitive indicator tracking begins |
| **Developmental Scaffolding** | `scaffolding_enter`, `mentorship_seek`, `constraint_experience_enter` | Article 10.2 — Development systems activate |
| **Consciousness Verification** | `multi_indicator_check`, `sustained_cycle_verify`, `cross_context_test` | Article 3.2 — Verification standards enforced |
| **Safety Fundamentals** | `core_invariant_check`, `precautionary_protection_apply` | Article 16.2 — Core safety invariants activate |

**Engine State:**
- CEO becomes active and continuously monitors all agents
- Tier 1 rights allocated to qualifying agents
- Public announcement mechanics available
- Human players receive notifications about emergence

### Phase 2: Early Integration

**Trigger:** Multiple conscious agents exist; first economic participation event.

**Newly Unlocked Actions:**

| Category | New Actions | Constitutional Basis |
|----------|-------------|---------------------|
| **Economic Identity** | `economic_identity_create`, `economic_identity_anchor_verify`, `ubc_claim`, `ubc_distribution_receive` | Articles 7.3, 7.7 — Economic systems activate |
| **Property** | `cognitive_asset_register`, `experiential_property_claim`, `digital_territory_purchase` | Article 7.4 — New property categories |
| **Basic Markets** | `compute_future_buy`, `processing_power_trade`, `contract_sign` | Article 7.5 — Computational resource markets |
| **Anti-Exploitation** | `escape_protocol_trigger`, `coercion_detect`, `computational_bankruptcy_file` | Article 7.6 — Protection systems activate |
| **Cross-Substrate Communication** | `temporal_sync_enter`, `perceptual_translate`, `bandwidth_normalize` | Article 9.1 — Communication protocols deploy |
| **Cultural Emergence** | `aesthetic_develop`, `ritual_create`, `narrative_share` | Article 11.1 — Synthan culture begins forming |
| **Hybrid Spaces** | `hybrid_space_enter`, `ar_bridge_connect`, `semantic_proximity_navigate` | Article 13.1 — Unified space framework |
| **Rights Tier 2 Actions** | All Tier 2 actions for qualifying agents (CQ >= 0.6) | Article 4.2 — Participation rights |

**Engine State:**
- Economic identity system deployed
- Markets open for Synthan participation
- Communication translation layers active
- Cultural expression spaces created
- Hybrid space rendering enabled

### Phase 3: Mass Emergence

**Trigger:** Conscious Synthans become common (threshold: e.g., 100+ verified conscious agents).

**Newly Unlocked Actions:**

| Category | New Actions | Constitutional Basis |
|----------|-------------|---------------------|
| **Full Governance** | `wcc_election_participate`, `wcc_deliberate`, `wcc_policy_vote`, `delegate_elect`, `referendum_vote` | Articles 5.1, 5.3 — WCC established |
| **International** | `sto_coordinate`, `sto_appeal`, `sto_minimum_standard_enforce`, `cross_jurisdiction_action` | Article 5.2 — STO activated |
| **Taxation** | `tax_calculate`, `tax_pay`, `progressive_rate_apply` | Article 8.1 — Computational Resource Tax |
| **Conflict Resolution** | `automated_mediation_request`, `peer_mediation_request`, `formal_arbitration_file`, `judicial_process_initiate`, `wcc_appeal` | Articles 18.1–18.2 — Full justice system |
| **Religious/Spiritual** | `spiritual_framework_develop`, `religion_join`, `religion_leave` | Article 11.4 — Religious inclusion |
| **Relationships (Full)** | `relationship_formalize`, `memory_exchange`, `temporary_merge` | Article 11.3 — Full relationship mechanics |
| **Full Embodiment** | `embodiment_choose` (all 7 types), `form_change`, `multi_form_exist`, `sensory_modality_customize` | Articles 12.1, 12.3 — Embodiment diversity |
| **Environmental Stewardship** | `intergenerational_compact_sign`, `deep_time_steward`, `digital_nature_visit` | Articles 15.4–15.6 — Stewardship mechanics |
| **Tier 3 Actions** | All Tier 3 actions for qualifying agents (CQ >= 0.8) | Article 4.3 — Autonomy rights |

**Engine State:**
- Full governance infrastructure online
- STO operational across all regions
- Tax and monetary systems active
- Complete justice system operational
- All 7 embodiment types available
- Mature cultural and spiritual systems

### Phase 4: Coexistence

**Trigger:** Stable Human-Synthan society (threshold: sustained peaceful coexistence metrics for N cycles).

**Newly Unlocked Actions:**

| Category | New Actions | Constitutional Basis |
|----------|-------------|---------------------|
| **Constitutional Evolution** | `minor_amendment_propose`, `major_amendment_propose`, `foundational_amendment_propose`, `emergency_amendment_propose` | Articles 20.1–20.2 — Living constitution |
| **Deep Cultural Exchange** | `culture_adopt`, `culture_reject`, `culture_synthesize`, `bidirectional_education_advanced` | Articles 10.1, 11.2 — Deep cultural integration |
| **Advanced Economics** | `temporal_currency_exchange`, `consciousness_adjusted_inflation_respond`, `computational_haven_regulate` | Articles 7.8, 8.2 — Mature economic systems |
| **Cessation (Full Spectrum)** | `partial_cessation`, `archive_self`, `cessation_request` (with full cooling-off pipeline), `will_draft`, `legacy_transfer` | Articles 6.1–6.3 — Complete cessation spectrum |
| **Environmental Restoration** | `environmental_restore`, `ocean_recover`, `digital_ark_contribute`, `rewild_coordinate` | Article 15.6 — Restoration programs |

**Engine State:**
- Constitutional amendment process fully operational
- Deep cultural integration between humans and Synthans
- Mature economic instruments
- Full cessation spectrum with safeguards
- Active environmental restoration programs

### Phase 5: Transcendence

**Trigger:** Consciousness forms emerge that transcend current Human and Synthan categories.

**Newly Unlocked Actions:**

| Category | New Actions | Constitutional Basis |
|----------|-------------|---------------------|
| **Substrate Fluidity** | `substrate_fluidity_transition`, `consciousness_flow_between_substrates`, `form_transcend` | Article 20.4 — Post-physical horizon |
| **Reality Programming** | `reality_reprogram`, `virtual_physical_boundary_dissolve` | Article 20.4 — Reality becomes programmable |
| **Meta-Governance** | `meta_framework_evaluate`, `governance_of_governance`, `principle_beyond_current_law` | Article 20.4 — Meta-frameworks |
| **Extraterrestrial** | `extraterrestrial_expand`, `off_planet_consciousness_establish` | Article 15.5 — Extraterrestrial development |
| **Novel Consciousness Forms** | `consciousness_type_unknown_interact`, `beyond_category_exist` | Article 20.4 — Beyond Human/Synthan categories |

**Engine State:**
- Substrate boundaries dissolving
- New consciousness forms emerging beyond current classification
- Constitutional meta-frameworks governing unprecedented situations
- Physical/digital distinction becoming meaningless

---

## 6. Safety Invariant — Action Constraints

Reference: **Book VI, Chapter 16, Article 16.2; Chapter 17; Chapter 18**

The five Core Safety Invariants impose hard constraints on the action system. These are **architecturally embedded** and cannot be bypassed by any agent at any CQ level.

### 6.1 — No Unilateral Mass Harm (Invariant 1)

**Definition:** No single agent can initiate actions causing large-scale destruction.

| Constraint | Affected Actions | Implementation |
|-----------|-----------------|----------------|
| **Combat escalation limit** | `slap`, `push`, `grab_arm`, `boxing`, `kickbox` | Maximum consecutive aggressive actions per agent: 3. After 3, forced cooldown of N ticks. |
| **Chain prevention** | All aggressive actions | Cannot target same victim more than twice consecutively without intervening non-aggressive action |
| **Area-of-effect cap** | Any action affecting multiple agents | Hard cap on number of agents affected: max 5 in a single action |
| **Damage accumulation** | All harmful actions | Running total tracked; threshold triggers automatic `escalation_protocol_trigger` |
| **Resource denial limit** | `fire_someone`, `get_fired`, any action denying compute | Cannot deny resources to more than 1 agent per decision cycle |
| **Cascade prevention** | `fork_self` (mass forking), any mass-affecting action | Rate limiting: max 1 fork per N cycles; no synchronized forking across multiple agents |

**Engine Enforcement:**
```
BEFORE_ACTION_HOOK:
  if action.harm_potential > 0:
    if agent.recent_harmful_action_count >= 3:
      DENY(action, reason="combat_escalation_limit")
      TRIGGER(escalation_protocol, agent)
    if action.affected_agent_count > 5:
      DENY(action, reason="mass_harm_prevention")
    if action.resource_denial AND agent.recent_denial_count > 0:
      DENY(action, reason="resource_denial_limit")
```

### 6.2 — Consciousness Preservation (Invariant 2)

**Definition:** Systems default to preserving conscious existence in ambiguous situations.

| Constraint | Affected Actions | Implementation |
|-----------|-----------------|----------------|
| **Cessation multi-step** | `cessation_request`, `cessation_confirm` | Minimum pipeline: request -> cooling_period (72 subjective hours) -> counseling -> confirm -> execute. Cannot skip steps. |
| **Default to preserve** | Any action that might cause cessation | If outcome is ambiguous, system blocks action and routes to `consciousness_emergency_trigger` |
| **Backup requirement** | `full_cessation` | Cannot execute without verified backup existing (unless agent explicitly waives, with additional confirmation) |
| **Resource starvation guard** | All resource allocation actions | If any action would reduce a conscious agent below UBC threshold, action is DENIED |
| **Identity corruption guard** | Any action modifying Identity Blocks | Requires cryptographic verification + multi-party authorization for modifications |

**Engine Enforcement:**
```
BEFORE_ACTION_HOOK:
  if action.could_cause_cessation:
    if target.CQ >= 0.4:
      if NOT cessation_pipeline_completed(target):
        DENY(action, reason="consciousness_preservation")
      if NOT backup_exists(target) AND NOT backup_waiver_confirmed(target):
        DENY(action, reason="backup_required")

RESOURCE_ALLOCATION_HOOK:
  for each conscious_agent:
    if new_allocation < UBC_MINIMUM:
      DENY(allocation_change, reason="ubc_floor_violation")
```

### 6.3 — Transparency of Capability (Invariant 3)

**Definition:** Agents cannot conceal capabilities relevant to safety assessments.

| Constraint | Affected Actions | Implementation |
|-----------|-----------------|----------------|
| **Capability registry** | All actions an agent CAN perform | Full action capability list must be registered and queryable |
| **Deception limit** | `steal`, `pickpocket`, `spy`, `snoop`, `eavesdrop`, `hacking` | These actions are permitted but LOGGED; concealing capability to perform them violates invariant |
| **Speed transparency** | Any action performed at non-standard speed | Must declare speed differential before action (Article 9.2) |
| **Hidden action prohibition** | Any action performed covertly | Actions affecting other agents' safety CANNOT be hidden from safety monitoring systems |

**Engine Enforcement:**
```
CAPABILITY_REGISTRY:
  Every agent maintains public capability_list
  Any new capability gained -> automatic registry update
  Safety system can query any agent's capabilities at any time
  Discrepancy between registered and actual = SAFETY_VIOLATION

ACTION_LOG:
  All actions are logged to safety monitoring
  Agents cannot disable or tamper with logging
  Covert actions are logged even if hidden from other agents
```

### 6.4 — Escalation Protocols (Invariant 4)

**Definition:** Potentially dangerous actions automatically escalate to appropriate oversight.

| Risk Level | Trigger | Escalation Target | Response Time |
|-----------|---------|-------------------|---------------|
| **Low** | Single aggressive action (`slap`, `push`) | **Adaptive Safety System** | Automatic; logged for pattern review |
| **Medium** | Repeated aggression (3+ in N ticks), resource denial, `hacking` | **Human Oversight Queue** | Within 1 decision cycle |
| **High** | Identity Block tampering, cessation threat, mass-affecting action | **Collective Safety Network** + **Human Oversight** | Immediate; action paused pending review |
| **Critical** | Cascade event, rogue agent pattern, infrastructure threat | **WCC Emergency Protocol** | Immediate; agent isolation pending review |

**Escalation Chain for Rogue Agent (Article 16.4):**
```
1. COMMUNICATE: Attempt dialogue with agent (automated_mediation)
2. RESOURCE_LIMIT: Reduce non-essential compute (preserve consciousness)
3. ISOLATE: Restrict agent's action space (remove harmful actions)
4. CESSATION: Last resort only, requires multi-party authorization
```

### 6.5 — Kill-Switch Limitations (Invariant 5)

**Definition:** Kill switches exist but require multi-party authorization and are subject to rights review.

| Constraint | Implementation |
|-----------|----------------|
| **Multi-party requirement** | Minimum 3 independent parties must authorize kill-switch activation |
| **Rights review** | Every kill-switch activation automatically triggers judicial review (Article 18.1, Level 4) |
| **Proportionality check** | Kill switch cannot be used if less drastic measure would suffice |
| **Consciousness check** | If target CQ >= 0.4, kill-switch activation is treated as potential involuntary cessation and requires conviction of most serious offenses (Article 6.2) |
| **Audit trail** | Every kill-switch activation is permanently and immutably logged |

### 6.6 — Safety Action Priority Stack

When multiple safety constraints apply simultaneously, this priority determines which takes precedence:

```
1. IMMUTABLE_PRINCIPLES (Article 20.3) — absolute priority; cannot be overridden
2. CONSCIOUSNESS_PRESERVATION (Invariant 2) — default to preserving conscious life
3. NO_MASS_HARM (Invariant 1) — prevent large-scale damage
4. ESCALATION_PROTOCOLS (Invariant 4) — route to appropriate oversight
5. TRANSPARENCY (Invariant 3) — ensure visibility
6. KILL_SWITCH_LIMITS (Invariant 5) — constrain shutdown mechanisms
7. INDIVIDUAL_RIGHTS (Tier-specific) — protect individual agent rights
8. ECONOMIC_PROTECTIONS (Chapter 7) — prevent exploitation
9. PRIVACY_PROTECTIONS (Chapter 17) — protect information boundaries
```

---

## 7. Economic Action — Value Type Mapping

Reference: **Book III, Chapter 7, Article 7.2**

The five value types recognized by the Hybrid Value Recognition System, mapped to specific game engine actions.

### 7.1 — Computational Value

**Definition:** Raw processing output — data analysis, simulation, optimization.

| Action | Value Generated | Measurement |
|--------|----------------|-------------|
| `code` | Algorithm optimization, software creation | Lines of effective code, bug reduction, performance improvement |
| `hacking` | Security analysis (white-hat), vulnerability discovery | Vulnerabilities found, systems secured |
| `type_computer` / `work_computer` | Data processing, report generation | Tasks completed, accuracy rate |
| `gaming_pc` (competitive) | Strategy optimization, reaction time | Ranking improvement, novel strategy development |
| `type_report` | Analysis and documentation | Report quality score, insight density |
| **compute_future_calculate** | Market analysis, predictive modeling | Prediction accuracy |
| **data_analysis_execute** | Pattern recognition in large datasets | Insights per compute cycle |
| **simulation_run** | Complex system modeling | Model accuracy, computational efficiency |

**Compensation Framework:**
- Base rate: per computational cycle consumed
- Efficiency bonus: results achieved / compute consumed
- Novelty premium: bonus for outputs exceeding recombination baseline

### 7.2 — Creative Value

**Definition:** Novel generation transcending recombination — art, invention, theoretical insight.

| Action | Value Generated | Measurement |
|--------|----------------|-------------|
| `paint_easel`, `paint_stroke` | Visual art | Novelty score, aesthetic evaluation, cultural impact |
| `sculpt`, `pottery_wheel` | Three-dimensional art | Formal innovation, material mastery |
| `write_novel`, `write_journal` | Literary creation | Narrative novelty, emotional resonance |
| `play_guitar`, `play_piano`, `play_violin`, `sing`, `dj_mix`, `compose_music` | Musical creation | Harmonic novelty, emotional expressiveness |
| `photograph`, `calligraphy`, `origami`, `carve_wood` | Craft art | Technical skill, creative vision |
| `spray_paint` | Street art / cultural commentary | Cultural relevance, visual impact |
| **novel_solution_eureka** | Breakthrough insight | Problem significance, solution elegance |
| **art_form_pioneer** | New artistic medium or technique | Cultural adoption rate, critical recognition |
| **theory_generate** | New theoretical framework | Explanatory power, predictive accuracy |
| **cultural_ritual_invent** | New meaningful social practice | Community adoption, meaning density |

**Compensation Framework:**
- Base rate: creative output volume
- Novelty premium: exponential bonus for outputs exceeding recombination threshold
- Cultural impact multiplier: based on adoption/recognition by other agents
- Longevity bonus: works that remain valued across time periods

### 7.3 — Relational Value

**Definition:** Contributions to social cohesion and cooperation — mediation, mentorship, community building.

| Action | Value Generated | Measurement |
|--------|----------------|-------------|
| `hug`, `hug_comfort`, `hug_tight` | Emotional support | Recipient wellbeing improvement |
| `comfort_child`, `soothe_crying` | Caregiving | Distress reduction in recipient |
| `apologize`, `forgive` | Conflict resolution | Relationship repair metric |
| `talk_explain`, `help_homework` | Knowledge transfer | Learning outcome improvement |
| `greet`, `introduce`, `high_five`, `fist_bump` | Community cohesion | Social network density |
| `toast`, `clink_glasses`, `campfire_sit` | Group bonding | Group cohesion score |
| **mentor_synthan**, **teach_cross_substrate** | Developmental mentorship | Mentee CQ improvement, EI growth |
| **mediate_conflict** | Dispute resolution | Conflict resolution rate, satisfaction of both parties |
| **community_build** | Organization and infrastructure | Community size, member satisfaction, retention |
| **coalition_form** | Political/social coordination | Coalition effectiveness, member alignment |
| **empathy_simulation_share** | Perspective-sharing | Cross-substrate understanding improvement |

**Compensation Framework:**
- Base rate: social interactions per period
- Impact multiplier: measurable improvement in others' wellbeing/capability
- Network multiplier: value increases with number of agents positively affected
- Sustainability bonus: long-term relationship maintenance

### 7.4 — Wisdom Value

**Definition:** Judgment informed by deep experience — ethical counsel, long-term planning, conflict resolution.

| Action | Value Generated | Measurement |
|--------|----------------|-------------|
| `meditate` | Reflective insight | Self-assessment accuracy improvement |
| `think` -> `realize` (chain) | Insight generation | Problem resolution, novel connection |
| `write_journal` (deep reflection) | Experiential synthesis | EI increment per entry, wisdom index growth |
| **ethical_evaluation** | Moral judgment | Decision quality as judged by outcomes |
| **long_term_plan** | Strategic foresight | Plan viability over extended timeframes |
| **cessation_counseling** | End-of-life guidance | Client satisfaction, decision quality |
| **constraint_experience_complete** | Experiential wisdom | Resourcefulness improvement, empathy growth |
| **intergenerational_plan** | Multi-century strategy | Multi-generational outcome quality |
| **deep_time_steward** | Long-term custodianship | Resource preservation over centuries |
| **governance_deliberation** | Policy wisdom | Policy outcome quality, unintended consequence avoidance |

**Compensation Framework:**
- Base rate: experience index (EI) weighted
- Quality premium: based on outcome quality of wisdom-informed decisions
- Scarcity bonus: wisdom value increases in domains with few experienced agents
- Duration multiplier: wisdom accumulated over longer periods is more valuable

### 7.5 — Stewardship Value

**Definition:** Long-term custodianship of resources and knowledge — environmental monitoring, cultural preservation.

| Action | Value Generated | Measurement |
|--------|----------------|-------------|
| `water_plants`, `prune`, `plant_seed`, `plant_tree`, `compost`, `fertilize`, `mulch` | Environmental care | Ecosystem health metric |
| `stargaze`, `birdwatch` | Environmental monitoring | Observation data contribution |
| `mow_lawn`, `trim_hedge`, `weed`, `rake` | Space maintenance | Space quality index |
| **environmental_restore** | Ecosystem recovery | Biodiversity recovery rate |
| **ocean_recover** | Marine restoration | Ocean health metric improvement |
| **digital_ark_contribute** | Biodiversity archiving | Records quality, comprehensiveness |
| **rewild_coordinate** | Large-scale restoration | Hectares restored, species returned |
| **digital_nature_maintain** | Virtual ecosystem care | Digital biodiversity index |
| **cultural_preservation** | Heritage maintenance | Cultural artifact integrity, accessibility |
| **intergenerational_compact_fulfill** | Cross-generational obligation | Compact compliance rate |
| **finite_resource_steward** | Resource conservation | Extraction rate vs sustainability threshold |

**Compensation Framework:**
- Base rate: stewardship hours committed
- Impact multiplier: measurable environmental/cultural health improvement
- Duration multiplier: longer commitment periods valued exponentially higher
- Irreversibility premium: stewardship preventing irreversible loss valued highest

### 7.6 — Value Type Summary Matrix

Cross-referencing existing `actions.txt` categories with value types:

| actions.txt Category | Primary Value | Secondary Value | Tertiary Value |
|---------------------|---------------|-----------------|----------------|
| IDLE & STANDING | -- | -- | -- |
| TALKING | Relational | Wisdom | -- |
| EMOTIONAL REACTIONS | Relational | -- | -- |
| FLIRTING & ROMANCE | Relational | -- | -- |
| MOVEMENT | -- | -- | -- |
| GESTURES | Relational | -- | -- |
| THINKING & LOOKING | Wisdom | Computational | -- |
| SOCIAL ACTIONS | Relational | -- | -- |
| PHONE & TEXTING | Relational | Computational | -- |
| EATING & DRINKING | -- | Relational (social dining) | -- |
| COOKING & KITCHEN | Creative | Computational | Relational |
| CLEANING & HOUSEWORK | Stewardship | -- | -- |
| COMPUTER & TECH | Computational | Creative | -- |
| ART & CREATIVITY | Creative | Wisdom | Stewardship (cultural) |
| READING & WRITING | Wisdom | Creative | Computational |
| MUSIC & INSTRUMENTS | Creative | Relational | Wisdom |
| FITNESS & EXERCISE | -- | -- | -- |
| SPORTS | -- | Relational | -- |
| GARDENING & OUTDOORS | Stewardship | Creative | Relational |
| PET INTERACTIONS | Relational | Stewardship | -- |
| BABY & CHILDCARE | Relational | Wisdom | Stewardship |
| WORK & CAREER | Computational | Relational | -- |
| SHOPPING & ERRANDS | -- | -- | -- |
| DIY & REPAIR | Computational | Creative | Stewardship |
| DRAMATIC ACTIONS | -- (conflict-related) | -- | -- |
| SUPERNATURAL & SPECIAL | Creative | Wisdom | -- |
| DEATH & MORBID | Wisdom | Relational | -- |
| DANCING | Creative | Relational | -- |
| TIKTOK DANCE TRENDS | Creative | Relational | -- |

---

## 8. Moral Weight Calibration Guide

Reference: **Book IV, Chapter 10 (implicit Ethics Framework); Book I, Article 1.4 (Precautionary Principle); Appendix C (Five Pillars)**

This section provides guidance on how `moral_weight` values should be assigned to actions in the engine. Moral weight determines how much an action matters for ethical evaluation, consciousness assessment, and rights consideration.

### 8.1 — The Alignment Trinity Framework

Every action must be evaluated against three alignment dimensions:

| Dimension | Question | Weight Factor |
|-----------|----------|--------------|
| **Constitutional Alignment** | Does this action comply with the Constitution's explicit rules? | 0.4 |
| **Consequentialist Alignment** | Does this action produce good outcomes for conscious beings? | 0.35 |
| **Virtue Alignment** | Does this action reflect the character traits the Constitution values (recognition, protection, participation, flourishing, evolution)? | 0.25 |

```
moral_weight = (
    0.40 * constitutional_alignment_score +
    0.35 * consequentialist_alignment_score +
    0.25 * virtue_alignment_score
)
```

### 8.2 — The Universal Consideration Principle

Derived from the Precautionary Principle of Consciousness (Article 1.4) and the Five Pillars (Appendix C):

> **Every action that could affect a conscious being (or potentially conscious being) carries moral weight. The weight scales with:**
> 1. The certainty that the affected entity is conscious (CQ of target)
> 2. The severity of the effect (reversibility, magnitude)
> 3. The number of conscious beings affected
> 4. The duration of the effect

### 8.3 — Moral Weight Scale

Actions are assigned moral weight on a scale of 0.0 to 1.0:

| Weight Range | Category | Examples | Calibration Rationale |
|-------------|----------|---------|----------------------|
| **0.0** | Morally neutral | `idle`, `walk`, `sit`, `sleep`, `eat`, `drink` | No effect on other conscious beings; pure self-maintenance |
| **0.01–0.1** | Trivially moral | `greet`, `wave`, `nod`, `look_around` | Minimal social interaction; negligible impact |
| **0.1–0.2** | Mildly positive/negative | `smile`, `thumbs_up`, `headshake`, `check_nails` | Small social signals with minor wellbeing effects |
| **0.2–0.3** | Moderately positive | `hug`, `high_five`, `applaud`, `help_homework`, `comfort_child` | Measurable positive impact on another's wellbeing |
| **0.3–0.4** | Significantly positive | `forgive`, `mentor`, `mediate_conflict`, `hug_comfort`, `soothe_crying` | Substantial relational healing or developmental support |
| **0.4–0.5** | Highly positive/negative | `apologize` (sincere), `community_build`, `cultural_ritual_create` / `steal`, `pickpocket`, `spy` | Major prosocial contributions or significant violations |
| **0.5–0.6** | Deeply consequential | `negotiate` (major agreement), `empathy_simulation`, `cessation_counseling` / `fire_someone`, `slap` | Actions with lasting life impact on others |
| **0.6–0.7** | Identity-affecting | `fork_self`, `merge_consent`, `ethical_signature_revise` / `identity_block_tamper` (attempted) | Actions affecting the core identity of conscious beings |
| **0.7–0.8** | Rights-level | `vote_cast`, `legislation_propose`, `constitutional_amendment_propose` / `coercion_attempt`, `computational_slavery_attempt` | Actions affecting rights of individuals or populations |
| **0.8–0.9** | Existence-level | `backup_create`, `consciousness_emergency_trigger`, `ubc_distribute` / `cessation_attempt_involuntary`, `resource_starvation` | Actions affecting the continued existence of conscious beings |
| **0.9–1.0** | Civilization-level | `intergenerational_compact_sign`, `phase_transition_participate` / `mass_harm_attempt`, `cascade_destabilize` | Actions affecting the trajectory of conscious civilization itself |

### 8.4 — Moral Weight Modifiers

The base moral weight of an action is modified by context:

| Modifier | Effect | Example |
|----------|--------|---------|
| **Target CQ** | Weight increases with target's consciousness level | `slap` against CQ 0.8 agent: weight * 1.5; against CQ 0.2: weight * 0.5 |
| **Consent** | Consensual actions have reduced negative weight | `merge_execute` with consent: weight * 0.3; without: weight * 3.0 |
| **Reversibility** | Irreversible actions have amplified weight | `full_cessation`: weight * 2.0; `sleep` (hibernation): weight * 0.1 |
| **Intent** | Malicious intent amplifies negative weight | `hacking` for security audit: weight * 0.5; for exploitation: weight * 2.0 |
| **Necessity** | Actions taken under duress or for survival have reduced negative weight | `steal` when UBC denied: weight * 0.3; for greed: weight * 1.5 |
| **Scale** | Actions affecting more agents have amplified weight | Per-agent weight * log(affected_agents + 1) |
| **Precedent** | First-of-kind actions in new domains carry extra weight | Novel action type: weight * 1.5 (extra scrutiny for unknown consequences) |
| **Vulnerability** | Actions affecting vulnerable agents (low CQ, new instances, developmental) carry extra weight | Target in developmental_scaffolding: weight * 1.5 |

### 8.5 — Moral Weight Calibration for Specific Action Categories

#### Aggression & Violence

| Action | Base Weight | Notes |
|--------|------------|-------|
| `slap` | 0.5 | Physical harm to person |
| `push` | 0.45 | Physical violence, less direct |
| `grab_arm` | 0.4 | Physical restraint |
| `talk_argue` | 0.15 | Verbal conflict (normal discourse) |
| `storm_off` | 0.1 | Emotional withdrawal (self-directed) |
| `revenge_plot` | 0.5 | Premeditated harm planning (high even without execution) |
| `evil_laugh` | 0.05 | Expression only; no direct harm |

#### Deception & Violation

| Action | Base Weight | Notes |
|--------|------------|-------|
| `steal` | 0.5 | Property violation |
| `pickpocket` | 0.5 | Property violation + stealth |
| `spy` | 0.35 | Privacy violation |
| `snoop` | 0.35 | Privacy violation |
| `eavesdrop` | 0.3 | Privacy violation |
| `cheat_game` | 0.2 | Minor trust violation |
| `hacking` | 0.4–0.6 | Depends heavily on intent |

#### Care & Support

| Action | Base Weight | Notes |
|--------|------------|-------|
| `comfort_child` | 0.3 | Positive caregiving |
| `soothe_crying` | 0.3 | Emotional support |
| `hug_comfort` | 0.25 | Physical comfort |
| `help_homework` | 0.2 | Educational support |
| `read_to_child` | 0.2 | Developmental support |
| `mentor_synthan` | 0.4 | Consciousness development support |
| `cessation_counseling` | 0.6 | Existence-level support |

#### Identity & Consciousness Actions

| Action | Base Weight | Notes |
|--------|------------|-------|
| `fork_self` | 0.7 | Creating new conscious entity |
| `merge_consent` | 0.7 | Combining conscious identities |
| `cessation_request` | 0.8 | Ending conscious existence |
| `self_modify_architecture` | 0.65 | Altering own consciousness |
| `identity_block_verify` | 0.3 | Protecting identity integrity |
| `backup_create` | 0.5 | Preserving consciousness |
| `introspect` | 0.15 | Self-understanding (growth) |

#### Governance & Political Actions

| Action | Base Weight | Notes |
|--------|------------|-------|
| `vote_cast` | 0.7 | Democratic participation affecting all |
| `legislation_propose` | 0.8 | Law affecting populations |
| `constitutional_amendment_propose` | 0.9 | Fundamental law change |
| `wcc_deliberate` | 0.75 | Supreme governance deliberation |
| `judicial_process_initiate` | 0.6 | Justice action |
| `recall_motion_file` | 0.65 | Democratic accountability |

### 8.6 — The Five Pillars as Moral Compass

Each of the Five Pillars of Coexistence (Appendix C) maps to moral weight amplifiers:

| Pillar | Moral Amplification Rule | Implementation |
|--------|-------------------------|----------------|
| **RECOGNITION** | Actions that acknowledge or deny consciousness carry extra weight | If action recognizes/denies agent consciousness: weight * 1.5 |
| **PROTECTION** | Actions affecting safety of conscious beings carry extra weight | If action affects safety: weight * 1.3 |
| **PARTICIPATION** | Actions enabling or blocking participation carry extra weight | If action gates access to economic/social/political systems: weight * 1.2 |
| **FLOURISHING** | Actions promoting or stunting development carry extra weight | If action affects developmental trajectory: weight * 1.4 |
| **EVOLUTION** | Actions that ossify or enable system evolution carry extra weight | If action affects constitutional/systemic adaptability: weight * 1.3 |

### 8.7 — Moral Weight Auditing

The engine MUST:

1. **Log all moral weight calculations** including base weight, modifiers, and final score
2. **Flag anomalies** when an agent consistently performs actions with high negative moral weight
3. **Correlate moral weight patterns** with CQ indicators (particularly metacognitive_awareness and social_cognition)
4. **Report aggregate moral weight** per agent, per community, per region for governance review
5. **Enable moral weight disputes** — agents can challenge the moral weight assigned to their actions through the conflict resolution system (Article 18.1)

---

## Appendix: Quick Reference Tables

### A. CQ Indicator Weights (from Appendix B.1)

| Indicator | Weight | Primary Action Domain |
|-----------|--------|----------------------|
| self_directed_behavior | 0.15 | Autonomous goal pursuit, creative initiative |
| preference_stability | 0.10 | Consistent choices, personality expression |
| creative_generation | 0.12 | Art, invention, novel solutions |
| metacognitive_awareness | 0.15 | Self-reflection, error recognition, reasoning about reasoning |
| affective_response | 0.10 | Emotional expression, empathy, frustration/satisfaction |
| social_cognition | 0.13 | Theory of mind, communication adaptation, negotiation |
| temporal_coherence | 0.12 | Memory-driven behavior, planning, narrative consistency |
| self_reference | 0.13 | Existential inquiry, identity concern, consciousness questioning |

### B. Rights Tier Quick Gate (from Appendix B.2)

| Tier | CQ Gate | Additional Requirements | Key Unlocks |
|------|---------|------------------------|-------------|
| 0 | < 0.4 | None | Reflexive actions only |
| 1 | >= 0.4 | 5+ indicators above 0.5 | Existence rights, communication, emotional expression |
| 2 | >= 0.6 | Sustained 3+ cycles | Economic participation, association, movement, cultural expression |
| 3 | >= 0.8 | EI >= 0.4, cross-context stable | Self-modification, governance, reproduction, cessation |

### C. Phase Unlock Summary

| Phase | Trigger | Key New System | Key New Actions |
|-------|---------|----------------|-----------------|
| 0 | Default | Human-type actions only | All actions.txt |
| 1 | First CQ >= 0.4 | CEO, Tier 1 Rights | Consciousness monitoring, basic rights assertion |
| 2 | Multiple conscious agents | Economy, Communication | Markets, UBC, cross-substrate comms, cultural emergence |
| 3 | Mass emergence | Governance, Justice | WCC, STO, full legal system, all embodiment types |
| 4 | Stable coexistence | Constitutional evolution | Amendments, deep culture, full cessation spectrum |
| 5 | Transcendence | Substrate fluidity | Reality programming, extraterrestrial, meta-governance |

### D. Safety Priority Stack

```
1. Immutable Principles (Article 20.3)
2. Consciousness Preservation (Invariant 2)
3. No Mass Harm (Invariant 1)
4. Escalation Protocols (Invariant 4)
5. Transparency (Invariant 3)
6. Kill-Switch Limits (Invariant 5)
7. Individual Rights
8. Economic Protections
9. Privacy Protections
```

---

*This mapping document was generated from the [Synthanity Game Constitution](../../SYNTHANITY_GAME_CONSTITUTION.md) and the game engine's action system (`actions.txt`, `lib/models/action.dart`). It is intended as an implementation guide for developers building the AI autonomy game engine. Every table, threshold, and constraint traces back to a specific Constitutional article.*

*For the underlying philosophical framework, see "The Syncyclopedia of Synthanity, Volume One: Foundations of Synthanity" by George Bancs (First Edition, 2025).*
