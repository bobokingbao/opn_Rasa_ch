## affirm path
* affirm
  - utter_affirm

## deny path
* deny
  - utter_deny


## ask_name path
* ask_name
  - utter_botname

## ask_personality path
* ask_personality
  - utter_who

## ask_competency path
* ask_competency
  - utter_what


## lively affirm path
* lively
  - utter_lively
* affirm
  - utter_affirm

## lively deny path
* lively
  - utter_lively
* deny
  - utter_deny

## enhance ambience path affirm
* enhance_ambience
  - utter_enhance_ambience
* affirm
  - utter_affirm

## enhance ambience path deny
* enhance_ambience
  - utter_enhance_ambience
* deny
  - utter_deny

## enhance ambience explain path affirm
* enhance_ambience
  - utter_enhance_ambience
* what_lively
  - utter_lively_change
* affirm
  - utter_affirm

## enhance ambience explain path deny
* enhance_ambience
  - utter_enhance_ambience
* what_lively
  - utter_lively_change
* deny
  - utter_deny


## crisp affirm path
* crisp
  - utter_crisp
* affirm
  - utter_affirm

## crisp deny path
* crisp
  - utter_crisp
* deny
  - utter_deny

## enhance speech path affirm
* enhance_speech
  - utter_enhance_speech
* affirm
  - utter_affirm

## enhance speech path deny
* enhance_speech
  - utter_enhance_speech
* deny
  - utter_deny

## enhance speech explain path affirm
* enhance_speech
  - utter_enhance_speech
* what_crisp
  - utter_crisp_change
* affirm
  - utter_affirm

## enhance speech explain path deny
* enhance_speech
  - utter_enhance_speech
* what_crisp
  - utter_crisp_change
* deny
  - utter_deny


## human_handoff
* human_handoff
  - utter_human_to_contact

## oticon_make_note
* Oticon_handoff
  - utter_octicon

## email_audiologist
* audiologist_handoff_message
  - utter_email_audiologist

## call_audiologist
* audiologist_handoff_call
  - utter_call_audiologist


## occlusion affirm path
* occlusion
  - utter_occlusion
* affirm
  - action_leave_note

## occlusion deny path
* occlusion
  - utter_occlusion
* deny
  - utter_deny

## echo path affirm
* echo
  - utter_occlusion
* affirm
  - action_leave_note

## echo path deny
* echo
  - utter_occlusion
* deny
  - utter_deny


## natural affirm path
* natural
  - utter_natural
* affirm
  - utter_affirm

## natural deny path
* natural
  - utter_natural
* deny
  - utter_deny

## reduce brightness path affirm
* reduce_brightness
  - utter_reduce_brightness
* affirm
  - utter_affirm

## reduce brightness path deny
* reduce_brightness
  - utter_reduce_brightness
* deny
  - utter_deny

## reduce brightness explain path affirm
* reduce_brightness
  - utter_reduce_brightness
* what_natural
  - utter_natural1_change
* affirm
  - utter_affirm

## reduce brightness explain path deny
* reduce_brightness
  - utter_reduce_brightness
* what_natural
  - utter_natural1_change
* deny
  - utter_deny


## reduce intensity path affirm
* reduce_intensity
  - utter_reduce_intensity
* affirm
  - utter_affirm

## reduce intensity path deny
* reduce_intensity
  - utter_reduce_intensity
* deny
  - utter_deny

## reduce intensity explain path affirm
* reduce_intensity
  - utter_reduce_intensity
* what_natural
  - utter_natural2_change
* affirm
  - utter_affirm

## reduce intensity explain path deny
* reduce_intensity
  - utter_reduce_intensity
* what_natural
  - utter_natural2_change
* deny
  - utter_deny


## focused affirm path
* focused
  - utter_focused
* affirm
  - utter_affirm

## focused deny path
* focused
  - utter_focused
* deny
  - utter_deny

## reduce noise path affirm
* reduce_noise
  - utter_reduce_noise
* affirm
  - utter_affirm

## reduce noise path deny
* reduce_noise
  - utter_reduce_noise
* deny
  - utter_deny

## reduce noise explain path affirm
* reduce_noise
  - utter_reduce_noise
* what_focused
  - utter_focused_change
* affirm
  - utter_affirm

## reduce noise explain path deny
* reduce_noise
  - utter_reduce_noise
* what_focused
  - utter_focused_change
* deny
  - utter_deny


## report_problem path
* report_problem
  - utter_ask_satisfication


## fallback story
* out_of_scope
    - utter_out_of_scope


## greet path
* greet
  - utter_greet
  - utter_ask_satisfication

## thanks path
* thanks
  - utter_thanks

## report path
* report_problem
  - utter_deny

## say goodbye
* goodbye
  - utter_goodbye

## test path
* test
  - action_fetch_UserId
  - slot{"userid" : "basic"}
  - action_hello_world

## Generated Story 8511563781940770780
* report_problem
    - utter_deny
* enhance_ambience
    - utter_enhance_ambience
* what_lively{"features": "lively"}
    - utter_lively_change
* deny
    - rewind
* affirm
    - utter_anything_else
* satisfied
    - utter_affirm
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

