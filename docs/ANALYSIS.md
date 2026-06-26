# 8 Ball Pool HCI Analysis

## Product Analysis: 8 Ball Pool

### 1. Name and Domain

- **Product name:** 8 Ball Pool
- **Domain:** Mobile sports/e-sports game based on real-world billiards.
- **Platform:** Mobile app version on smartphones and tablets.

### 2. Target Users

#### 2.1 Casual Players

- **Description:** Users who play 8 Ball Pool for quick entertainment and relaxation.
- **Typical context:** Playing during free time, while resting, commuting, or waiting between activities.
- **Main needs:** Simple controls, fast matchmaking, short matches, and clear visual feedback so they can start and finish a game easily.

#### 2.2 Competitive Players

- **Description:** Users who play regularly to improve their ranking, earn coins, unlock cues, and compete in higher-level matches.
- **Typical context:** Playing with focus for longer sessions, often trying to win matches and progress in the game.
- **Main needs:** Accurate aiming controls, predictable shot power adjustment, fair matchmaking, and clear information about rules, rewards, and rankings.

#### 2.3 Beginner Players

- **Description:** New users who may not fully understand the rules of 8-ball pool or the meaning of the game's icons and features.
- **Typical context:** Playing their first few matches and learning the interface through trial and error.
- **Main needs:** Clear guidance, understandable icons, tutorials, and feedback that explains why a shot is valid, invalid, successful, or unsuccessful.

### 3. Core Use Cases

#### Use Case 1: Playing a quick online match

- **Goal:** Play a competitive pool match and earn coins/rewards.

- **Context:** This is the most common use case. Sessions typically last 3–10 minutes, making them suitable during breaks, commuting, waiting in line, or relaxing at home.

- **Where and When:**
  + Sitting at home on a sofa or bed.
  + Sitting in a café.
  + Sitting on public transportation.
  + Waiting at a bus stop, doctor's office, or school.
  + During short work or study breaks.

- **User situation:**
  + Usually seated.
  + Occasionally standing while waiting somewhere.
  + Rarely used while walking because aiming requires precision.

- **Interaction method:**
  + Tap buttons to navigate menus.
  + Drag finger to aim cue.
  + Pull power meter to control shot strength.
  + Tap chat/emote buttons.

- **Interaction flow:**
  1. Open game.
  2. Select game mode.
  3. Choose table.
  4. Wait for matchmaking.
  5. Play match.
  6. View results and rewards.
  7. Return to main menu.

#### Use Case 2: Managing and Upgrading Equipment

- **Goal:** Improve cue performance and customize equipment to gain advantages in future matches.

- **Context:** Players collect and upgrade cues to improve attributes such as power, aim, spin, and time available per turn.

- **Where and When:**
  + Between matches.
  + During downtime when users do not want to actively play.
  + While waiting for rewards, friends, or energy systems in other games.

- **User situation:**
  + Sitting on a sofa, chair, or bed.
  + Lying down while casually browsing menus.
  + Casual interaction requiring less concentration than gameplay.

- **Interaction method:**
  + Tap inventory and equipment menus.
  + Scroll through available cues.
  + View cue statistics and upgrade information.
  + Tap upgrade buttons to spend in-game currency.
  + Equip preferred cues through menu navigation.

- **Interaction flow:**
  1. Open inventory or cue collection menu.
  2. Browse available cues.
  3. Select a cue.
  4. Review statistics and upgrade options.
  5. Upgrade cue using available resources.
  6. Equip desired cue.
  7. Return to main menu or start a match.

#### Use Case 3: Collecting Rewards and Progression

- **Goal:** Claim rewards, monitor progression, and earn resources for future gameplay.

- **Context:** Users log in daily to claim rewards, open victory boxes, complete missions, and track progression.

- **Where and When:**
  + During daily login sessions.
  + During short breaks throughout the day.
  + Immediately after launching the game.
  + After completing matches.

- **User situation:**
  + Sitting, standing, lying down, or walking slowly.
  + Minimal attention and physical effort required.
  + Often performed as a quick routine activity.

- **Interaction method:**
  + Tap reward notifications.
  + Open victory boxes or reward containers.
  + Tap buttons to claim daily rewards.
  + Navigate mission and achievement screens.
  + Review progression indicators and level information.

- **Interaction flow:**
  1. Open the game.
  2. View available rewards and notifications.
  3. Claim daily rewards.
  4. Open victory boxes or reward containers.
  5. Review completed missions and achievements.
  6. Check progression status and earned resources.
  7. Return to the main menu or start another activity.

#### Use Case 4: Social Communication During Matches

- **Goal:** Express emotions, interact with opponents or friends, and enhance social engagement during gameplay.

- **Context:** Players communicate using predefined chat messages, emojis, and reactions during gameplay.

- **Where and When:**
  + During online matches.
  + Particularly common when playing against friends.
  + During competitive or casual game sessions.

- **User situation:**
  + Sitting or standing.
  + Multitasking between gameplay and communication.
  + Maintaining focus on the match while interacting socially.

- **Interaction method:**
  + Tap chat or emoji buttons.
  + Select predefined messages or reactions.
  + Send quick social responses without typing.
  + View incoming messages displayed on-screen.

- **Interaction flow:**
  1. Enter an online match.
  2. Open chat or emoji menu.
  3. Select a predefined message or reaction.
  4. Send message to opponent or friend.
  5. Receive and view responses.
  6. Continue gameplay while communication remains available.
  7. Finish match and return to menu.


### 4. Interface Benefits Based on HCI Concepts

#### 4.1. Gameplay interface mirrors real-world billiards

##### 4.1.1. Mental model
- **Why it's related:** The game presents objects that exist in real billiards: cue stick, cue ball, object balls, pockets, and table. Players already have expectations about how these objects behave.
- **Benefit:** Players can transfer existing knowledge from real billiards into the game, reducing learning effort.
- **Example:** A player who has played billiards before knows that hitting the cue ball into another ball will transfer momentum and potentially send the target ball into a pocket. When they start their first match, they can immediately predict what will happen without reading instructions.

##### 4.1.2. Natural mapping
- **Why it's related:** The controls resemble physical actions performed in real billiards. Rotating the cue changes aiming direction, and pulling back farther increases shot power.
- **Benefit:** Users can understand controls intuitively because the relationship between action and result is direct.
- **Example:** A player wants to hit the ball harder. Instead of adjusting a numerical strength value, they pull the cue farther backward. The stronger pull naturally produces a stronger shot, matching real-world expectations.

##### 4.1.3. Interface metaphor
- **Why it's related:** The entire gameplay screen acts as a digital representation of a real pool table.
- **Benefit:** The metaphor helps users immediately recognize the purpose of interface elements.
- **Example:** A beginner opening the game for the first time sees a pool table with balls and pockets. Even without a tutorial, they can infer that the goal is to pocket balls using the cue ball.

#### 4.2. Aim Guideline Improves Shot Planning

##### 4.2.1. Recognition vs Recall
- **Why it's related:** The aim guideline visually shows the predicted path of the cue ball and target ball. Players do not need to remember billiard angles or estimate trajectories mentally.
- **Benefit:** Reduces cognitive load and makes shot planning easier, especially for beginners.
- **Example:** A new player wants to pocket a ball near a side pocket. Instead of calculating the angle themselves, they can immediately see the projected path displayed on the table and adjust their aim accordingly.

##### 4.2.2. Feedback
- **Why it's related:** The guideline updates continuously as the player changes the aiming direction.
- **Benefit:** Provides immediate feedback about the effects of user actions, allowing quick corrections before committing to a shot.
- **Example:** While adjusting aim, a player notices that the projected ball path no longer reaches the intended pocket. The guideline changes instantly, allowing them to readjust before shooting.

#### 4.3. Corner-Placed Controls Improve Mobile Use

##### 4.3.1. Reachability
- **Why it's related:** Frequently used controls such as cue adjustment, spin controls, and menu buttons are placed at the upper corners of the screen where thumbs can easily reach them.
- **Benefit:** Reduces physical effort and makes interactions more comfortable during gameplay.
- **Example:** A player sitting on a bus holds the phone with one hand. They can access important controls using only their thumb without repositioning their grip.

##### 4.3.2. Fitts' Law
- **Why it's related:** Frequently used buttons are relatively large and positioned within easy reach, reducing movement distance and increasing target size.
- **Benefit:** Allows faster and more accurate interactions, especially during time-limited turns.
- **Example:** During a match, a player quickly opens the spin menu before their turn timer expires. The button is large and located near the thumb's resting area, allowing fast selection with minimal chance of tapping the wrong target.

##### 4.3.3. One-Handed Usage
- **Why it's related:** The interface is designed so most common interactions can be performed using a single thumb.
- **Benefit:** Supports mobile usage in situations where the user cannot dedicate both hands to the device.
- **Example:** A player waiting in line at a store is holding a bag in one hand. They can still aim shots, adjust power, and navigate menus using their free hand without significant difficulty.

#### 4.4. Immediate Feedback After Each Shot

##### 4.4.1. Feedback
- **Why it's related:** The game immediately responds to player actions through ball movement, collision animations, sound effects, and turn indicators.
- **Benefit:** Players can instantly understand whether their shot was successful and what happened as a result.
- **Example:** After pocketing a ball, the player sees the ball fall into the pocket, hears the pocketing sound, and notices that their turn continues. The outcome of the shot is immediately clear without requiring additional explanation.

#### 4.5. Important Buttons Are Easy to Recognize

##### 4.5.1. Recognition Rather Than Recall
- **Why it's related:** Major functions such as Play, Cue, Shop, Rewards, and Events are represented with visible icons and labels.
- **Benefit:** Players can locate functions directly without remembering menu paths.
- **Example:** A player who wants to claim rewards can identify the reward icon from the home screen without remembering where the feature is located.

#### 4.6. Colorful Visual Design Increases Engagement

##### 4.6.1. Color Perception
- **Why it's related:** The interface uses bright colors to distinguish game elements, rewards, currencies, and progression systems.
- **Benefit:** Important information stands out and becomes easier to identify quickly.
- **Example:** Reward chests use gold and bright visual effects, drawing attention to claimable rewards among other interface elements.

##### 4.6.2. Satisfaction
- **Why it's related:** Animations, vibrant colors, and visual effects create a more enjoyable experience.
- **Benefit:** Makes interaction feel rewarding and engaging.
- **Example:** When a player wins a match, the game displays colorful animations, coins flying onto the screen, and celebratory effects, creating a stronger sense of achievement than a simple text message.

### 5. Interface Drawbacks Based on HCI Concepts

Each drawback below is judged using the fundamental HCI concepts: **human capabilities** (senses, cognition, and the motor system), the five **usability dimensions** (learnability, efficiency, memorability, errors, satisfaction), the **usability design principles** (visibility, accessibility, consistency, affordances, natural mapping, feedback, and Fitts's law), **mental models**, and **interaction metaphors**.

#### 5.1. Small-Screen Aiming Can Be Difficult

##### 5.1.1. Human capabilities – Motor system (dexterity and accuracy)
- **Why it's related:** The motor system is our output system, measured by range of movement, speed, strength, dexterity, and accuracy. Aiming requires fine, accurate thumb movement on a small touch surface.
- **Drawback:** Users may struggle to aim accurately, especially on a small phone, while playing standing, or when holding the device with one hand.
- **Example:** A player on a moving bus tries to pocket a ball near the corner pocket. Because the vehicle shakes and the screen is small, the thumb shifts the cue angle slightly and the shot misses, even though the user understood the correct direction.
- **Why it is a problem:** The motor system is often the cause of errors. An interface that depends on fine motor accuracy becomes harder for users with large fingers, shaky hands, or unstable playing conditions.

##### 5.1.2. Fitts's law (small target, high index of difficulty)
- **Why it's related:** Fitts's law states that movement time depends on the index of difficulty `log(D/S + 1)`, where `S` is the target size and `D` the distance. The exact correct aim angle behaves like a very small target while the cue ball must travel a long distance across the table.
- **Drawback:** Fine aim adjustment is slow and error-prone because a tiny effective target at a long distance has a high index of difficulty.
- **Example:** During a time-limited turn, a player repeatedly drags the cue left and right because the aim line keeps moving past the desired angle.
- **Why it is a problem:** A high index of difficulty means repeated correction wastes time and increases frustration, especially in competitive matches.

##### 5.1.3. Usability (efficiency and errors)
- **Why it's related:** Efficiency (how quickly users perform tasks) and errors (how often mistakes occur and how easily users recover) are two of the five usability dimensions.
- **Drawback:** The aiming control is less efficient when very small adjustments are needed, and it raises the error rate during a turn.
- **Example:** A player runs out of turn time while fine-tuning the angle and is forced into a rushed, inaccurate shot.
- **Why it is a problem:** Lower efficiency and a higher error rate degrade two measurable usability outcomes at once.

#### 5.2. Spin Control May Not Match Beginner Understanding

##### 5.2.1. Mental models (how the system works)
- **Why it's related:** A mental model is the user's internal construction of how a system works, used to predict what will happen next. The spin feature relies on a mental model of real billiards physics.
- **Drawback:** New users may not understand why moving the spin marker changes the cue ball's movement after contact.
- **Example:** A beginner moves the spin marker to the bottom of the cue ball without knowing it creates backspin. After the shot, the cue ball rolls backward unexpectedly, and the player may think the result is random or unfair.
- **Why it is a problem:** A design should not conflict with users' mental models. When system behaviour does not match the user's prediction, the interaction becomes confusing and the user must learn through mistakes.

##### 5.2.2. Feedback (no explanation before the shot)
- **Why it's related:** Actions should have immediate effects, and feedback can be visual, audio, or haptic. Spin produces a strong effect but gives little explanatory feedback before the shot is taken.
- **Drawback:** The interface does not clearly preview or explain what the chosen spin will do during normal gameplay.
- **Example:** A beginner keeps losing position after each shot because nothing on screen explains how spin will move the cue ball after impact.
- **Why it is a problem:** Without feedback connecting the action (moving the marker) to its result, a powerful feature stays hidden from the users who most need it.

##### 5.2.3. Usability (learnability)
- **Why it's related:** Learnability — how easy it is to learn to use the system — is a core usability dimension.
- **Drawback:** Spin is powerful but hard to learn without excessive trial and error.
- **Example:** A new player avoids spin entirely because they never learned what it does, while experienced players use it constantly.
- **Why it is a problem:** Weak learnability widens the gap between new and experienced players and slows the novice's progress along the learning curve.

#### 5.3. The Real Pool Table Metaphor Is Not Always Complete

##### 5.3.1. Interaction metaphors (own properties, may mislead)
- **Why it's related:** Interaction metaphors exploit knowledge users already have from another domain but also have their own properties. 8 Ball Pool uses a real pool table metaphor, yet control is through dragging and on-screen sliders rather than a physical cue.
- **Drawback:** Some actions feel less natural than real billiards because the digital metaphor adds its own abstract controls.
- **Example:** In real billiards, shot power comes from physically pushing the cue. In the game, the user pulls a vertical power meter on the side of the screen — efficient for mobile, but disconnected from the table metaphor.
- **Why it is a problem:** Metaphors can be potentially deceptive and misleading; here the metaphor only partially matches the real activity, so some users need extra learning time.

##### 5.3.2. Natural mapping (broken physical mapping)
- **Why it's related:** Natural mapping means the arrangement of controls matches the arrangement of their effects. A physical cue maps power directly to how hard you push it.
- **Drawback:** A separate side power meter breaks the direct physical mapping between cue movement and shot strength.
- **Example:** A real billiards player expects power to come from cue motion on the table, but the game splits aiming (on the table) from power (on a side bar).
- **Why it is a problem:** When the mapping is indirect, the action feels game-like rather than fully natural and must be re-learned.

##### 5.3.3. Mental models (expectation conflict)
- **Why it's related:** Users who know real billiards expect digital cue control to behave like physical cue movement.
- **Drawback:** The difference between real cue control and mobile slider control conflicts with that expectation.
- **Example:** A player instinctively tries to "pull the cue" on the table for power but must instead find a separate meter.
- **Why it is a problem:** The user must adjust their mental model from "playing physical pool" to "operating a mobile game interface."

#### 5.4. The Home Screen Can Overload the Main Task

##### 5.4.1. Cognition – Attention (selected and divided)
- **Why it's related:** Attention can be selected, focused, or divided. A crowded home screen forces the user to divide attention and visually search among many competing elements before acting.
- **Drawback:** Users who simply want to start a match are distracted by reward icons, event banners, daily bonuses, and shop prompts.
- **Example:** A casual player opens the app for one quick match but must scan colourful reward and event elements before locating the normal play option.
- **Why it is a problem:** Dividing attention across many bright, animated targets slows down identification of the single most important action.

##### 5.4.2. Cognition – Memory (short-term limit and chunking)
- **Why it's related:** Short-term (working) memory holds only about seven items for a short time. A dense screen presents far more competing options than can be processed at once, and they are not grouped into clear chunks.
- **Drawback:** Bright icons, badges, animations, and pop-ups overload the limited capacity the user has for the screen.
- **Example:** A user standing in line scans the screen and cannot immediately tell which element is "Play," because nothing is chunked or visually prioritised.
- **Why it is a problem:** Exceeding working-memory limits increases cognitive effort before the user can complete even a simple task.

##### 5.4.3. Usability (efficiency, visibility vs simplicity)
- **Why it's related:** Efficiency is a usability dimension, and there is a trade-off in which more visibility can reduce simplicity. A good interface should also reduce the user's memory load.
- **Drawback:** Making every feature visible at once makes the path to the most common action (play) less direct.
- **Example:** The most-used action competes for space with many lower-priority promotions, so starting a match takes extra steps.
- **Why it is a problem:** The interface trades simplicity for visibility, reducing efficiency for the player's primary goal.

#### 5.5. Turn Timer Can Pressure Slow or New Users

##### 5.5.1. Cognition (cognitive processor and processing time)
- **Why it's related:** In the human information-processing model, the cognitive processor needs time to interpret input before the motor processor acts. Players must read the table, identify legal shots, aim, set power, and sometimes spin.
- **Drawback:** A countdown timer can make beginners, older users, or distracted users feel rushed before processing is complete.
- **Example:** A beginner is still deciding between a solid and a striped ball when the timer runs low; they rush and hit the wrong ball.
- **Why it is a problem:** Forcing action before cognitive processing finishes increases stress and reduces accuracy for users who need more time.

##### 5.5.2. Usability (errors and satisfaction)
- **Why it's related:** Errors and satisfaction are two usability dimensions; a timer can increase mistakes and reduce satisfaction.
- **Drawback:** Users make avoidable mistakes because they act before they are ready.
- **Example:** A player who knows the correct shot runs out of time adjusting the cue and loses the turn.
- **Why it is a problem:** The player feels punished by interface timing rather than by their actual billiards skill, hurting satisfaction.

##### 5.5.3. Accessibility (cater to universal usability)
- **Why it's related:** Accessibility is a design goal: an interface should cater to universal usability for users with different cognitive and motor abilities.
- **Drawback:** A fixed timer does not accommodate users who process or move more slowly.
- **Example:** An older player or a player with a motor impairment cannot reliably complete a shot within the default time.
- **Why it is a problem:** A single timing assumption excludes part of the user community that the interface should support.

#### 5.6. Cue Statistics Can Be Hard to Interpret

##### 5.6.1. Mental models
- **Why it's related:** Mental models let users predict how a system behaves. Cue attributes such as force, aim, spin, and time are abstract statistics, so beginners cannot easily predict their effect on a match.
- **Drawback:** Users may choose or upgrade cues without understanding what each statistic actually does.
- **Example:** A new player picks a cue because it looks attractive, not realising another cue offers more aim support or more time per turn.
- **Why it is a problem:** Decisions based on appearance instead of an accurate mental model lead to poor use of limited resources.

##### 5.6.2. Recognition rather than recall
- **Why it's related:** Recognition (remembering with a visible cue) is easier than recall (remembering with no help). Raw numeric stats force users to recall what each attribute means rather than recognise it.
- **Drawback:** Without short explanations, users must remember from memory what "aim" or "time" changes in play.
- **Example:** A player upgrades a cue but later cannot tell whether power, spin, or aim improved in a noticeable way.
- **Why it is a problem:** Relying on recall instead of recognition reduces confidence and makes progression feel confusing.

##### 5.6.3. Interaction metaphors (cue becomes a game object)
- **Why it's related:** The cue is a real billiards object, but in the app it also becomes an upgradeable game item with numeric attributes — a metaphor with its own added properties.
- **Drawback:** This shifts the cue metaphor from a physical tool to a statistics-driven game object.
- **Example:** A user expects a cue to mainly affect appearance or feel, but the game links it to attributes such as time and aim.
- **Why it is a problem:** Metaphors may mislead; the digital cue has properties that do not match a real cue, so expectations break.

#### 5.7. Power Meter Can Cause Accidental Overpowered Shots

##### 5.7.1. Human capabilities – Motor system (dexterity and accuracy)
- **Why it's related:** The motor system's dexterity and accuracy limit how precisely a user can control dragging distance with a finger.
- **Drawback:** Users may pull slightly too far or release at the wrong moment, producing more power than intended.
- **Example:** A player wants a soft shot to leave the cue ball near the centre, but the thumb pulls the meter too far and the ball travels into a bad position.
- **Why it is a problem:** Small motor errors create large gameplay consequences, especially in close matches.

##### 5.7.2. Feedback (insufficient preview before release)
- **Why it's related:** Actions should have immediate effects; a power meter should give clear feedback about resulting strength before the user commits.
- **Drawback:** Users do not always get enough feedback about how strong the shot will be in the actual table situation.
- **Example:** A player pulls the meter to what looks like a medium level, but the ball travels farther than expected and scratches.
- **Why it is a problem:** Weak pre-release feedback breaks the link between meter position and final ball movement, increasing errors.

##### 5.7.3. Usability (error prevention and reversal)
- **Why it's related:** An interface should prevent errors and permit easy reversal of actions; preventing and recovering from errors is a usability dimension.
- **Drawback:** Once the meter is released the shot cannot be undone, so a small slip is unrecoverable.
- **Example:** An accidental overpowered shot immediately ends the turn with a scratch and no way to revert.
- **Why it is a problem:** With no error prevention and no reversal, a minor motor slip is punished severely.

#### 5.8. Chat and Emoji Reactions Can Distract During Shots

##### 5.8.1. Cognition – Attention (focused vs divided)
- **Why it's related:** Focused attention is on one task, while divided attention is split across several at once. A time-sensitive shot needs focused attention on the table, aim line, timer, and controls.
- **Drawback:** Incoming chat messages or emojis force the player to divide attention during a critical moment.
- **Example:** A player preparing a final shot is pulled away by an opponent spamming emojis, whose movement attracts the eye.
- **Why it is a problem:** Extra visual stimuli break focused attention and increase the chance of a mistake.

##### 5.8.2. Usability (errors and efficiency)
- **Why it's related:** Errors and efficiency are usability dimensions; the interface should help users focus on the main task.
- **Drawback:** Social features can interfere with the primary task of aiming and shooting.
- **Example:** A player accidentally taps the chat area while adjusting aim near the edge of the screen.
- **Why it is a problem:** Non-essential elements placed near gameplay controls cause input errors and reduce efficiency.

##### 5.8.3. User control and mental models
- **Why it's related:** Users should keep an internal locus of control; they expect a competitive game to protect their turn.
- **Drawback:** Repeated opponent reactions conflict with the user's expectation of a focused, protected aiming area.
- **Example:** A player expects opponent messages to stay secondary, but an emoji animation becomes visually prominent during a key shot.
- **Why it is a problem:** Removing the user's control over distractions conflicts with their mental model of a focused shot-taking environment.

#### 5.9. Reward and Event Icons Are Not Always Self-Explanatory

##### 5.9.1. Recognition rather than recall
- **Why it's related:** Recognition (with a visible, understandable cue) is easier than recall. Icons should let users recognise a function instead of recalling what an ambiguous symbol means.
- **Drawback:** Some reward, event, currency, or chest icons do not clearly communicate their purpose.
- **Example:** A returning player sees several icons but cannot tell which is a daily reward, which is an event, and which leads to a shop offer.
- **Why it is a problem:** When icons fail to support recognition, users fall back on recall or trial-and-error tapping.

##### 5.9.2. Consistency (metaphorical and internal)
- **Why it's related:** Internal and metaphorical consistency mean similar things should look similar and reflect real-world meaning.
- **Drawback:** Reward-like visuals are reused inconsistently, so similar-looking icons do different things.
- **Example:** A user wanting a free reward opens a paid offer screen by mistake because both use bright, reward-like visuals.
- **Why it is a problem:** Inconsistent visuals reduce learnability and memorability and erode trust in the interface.

##### 5.9.3. Interaction metaphors (inconsistent metaphors)
- **Why it's related:** Reward icons use metaphors such as boxes, coins, cash, and trophies, which may not be used consistently everywhere.
- **Drawback:** The same metaphor (e.g., a chest) can mean different things in different places.
- **Example:** A chest icon means a free reward in one place, a timed box in another, and a shop item elsewhere.
- **Why it is a problem:** Inconsistent metaphors make the interface less predictable and can mislead users.

#### 5.10. Menu Navigation Can Interrupt the Sports Experience

##### 5.10.1. Interaction metaphors (inconsistent use)
- **Why it's related:** Metaphors are highly learnable but can mislead when not used consistently. The gameplay screen uses a strong pool-table metaphor while the surrounding menus use mobile-game resource metaphors.
- **Drawback:** Moving between realistic billiards and resource-management menus makes the product feel less consistent.
- **Example:** After a match, the user shifts from a realistic table to screens about coins, boxes, cue upgrades, and limited-time events.
- **Why it is a problem:** The interaction style switches from "playing pool" to "managing mobile game resources," weakening the sports metaphor.

##### 5.10.2. Consistency and conceptual model
- **Why it's related:** A conceptual model consists of core activities, objects, and interface metaphors; internal consistency keeps that model stable across screens.
- **Drawback:** Frequent transitions between gameplay, rewards, shop, and upgrade screens fragment one consistent conceptual model.
- **Example:** A casual player wanting another match is routed through post-match rewards and upgrade prompts first.
- **Why it is a problem:** An inconsistent conceptual model adds steps between the user's intention and the next match.

##### 5.10.3. Usability (efficiency) and mental models
- **Why it's related:** Efficiency is a usability dimension, and the system flow should match the user's mental model of what they are doing (playing a sport).
- **Drawback:** Users who mainly want a billiards experience do not expect so many economy, event, and upgrade screens around each match.
- **Example:** A user finishes a match expecting to return to table selection but is guided through rewards and offers.
- **Why it is a problem:** When flow does not match the user's goal, efficiency and satisfaction both drop.

### 6. Difficulties for Different User Types and Contexts

Each difficulty is mapped to the specific human-capability or usability concept that explains it.

| User Type / Context | Possible Difficulty | Related Interface Element | HCI Concept | Explanation |
| --- | --- | --- | --- | --- |
| Beginner user | May not understand spin, cue statistics, reward icons, or table rules quickly. | Spin control, cue upgrade screen, reward/event icons, tutorials | Mental models; recognition vs recall; learnability | Beginners lack the mental model the interface assumes, and raw stats/icons force recall instead of recognition. Clearer labels and previews would raise learnability. |
| Expert user | May feel slowed by reward screens, menu transitions, and repeated prompts between matches. | Post-match rewards, shop prompts, event menus, table selection flow | Efficiency; power law of practice | Experts have moved up the learning curve and value efficiency; extra steps interrupt their fast, repeated workflow of starting another match. |
| User in motion | May miss shots because aiming and power control require precise finger movement. | Aim control, power meter, turn timer | Motor system (dexterity, accuracy); Fitts's law | Motor accuracy drops when standing, commuting, or using one hand, and small targets at long distance have a high index of difficulty. |
| User in poor lighting | May struggle to distinguish small icons, ball positions, or competing visual elements. | Pool table, ball colors, reward badges, menu icons | Human senses – vision (view frustum, color perception) | Only the small foveal region is high-detail, and glare plus dense colour reduce contrast; colour-only coding also fails for the 7–8% of males with red–green colour blindness. |
| User with accessibility needs | May have difficulty with small touch targets, time pressure, visual effects, or color-dependent information. | Aiming, power meter, timer, chat reactions, color-coded rewards | Accessibility; universal usability | Universal usability requires supporting varied motor, visual, and cognitive abilities through larger touch targets, calmer visuals, and adjustable timing. |
| Returning user (after a break) | May forget where features are or what icons mean. | Home screen layout, reward/event icons | Memorability; recognition vs recall | Memorability is how easily users re-establish proficiency; consistent, recognisable icons reduce the re-learning effort after time away. |

### 7. Potential Solutions Identification

For each drawback in Section 5, the proposed solution directly addresses the underlying HCI concept (a human capability, a usability dimension, a design principle, a mental model, or an interaction metaphor) and improves the experience for the affected users.

| Drawback (Section 5) | Proposed Solution | HCI Concept Addressed | How the Solution Helps |
| --- | --- | --- | --- |
| 5.1 Small-screen aiming is difficult | Add a precision aiming mode that slows cue rotation (enlarging the effective target) during small adjustments. | Motor system; Fitts's law; error prevention | Lowering the index of difficulty gives finer control and reduces missed shots from small finger movements. |
| 5.2 Spin control may not match beginner understanding | Show a short preview or label explaining top spin, backspin, and side spin before the shot. | Mental models; feedback; learnability | Immediate feedback aligns system behaviour with the user's prediction, so beginners learn without failed shots. |
| 5.3 Pool table metaphor is not always complete | Connect power control visually to cue movement, or offer an optional cue-pull control style. | Natural mapping; interaction metaphors | A more direct mapping reconnects shot power to the physical pool metaphor and feels more natural. |
| 5.4 Home screen can overload the main task | Make the Play action visually dominant and group rewards/events into clearly chunked secondary areas. | Attention; short-term memory (chunking); visibility vs simplicity | Chunking and a single dominant target respect working-memory limits and let users start a match faster. |
| 5.5 Turn timer can pressure slow or new users | Offer practice modes, clearer timer warnings, or slightly longer timers in low-stakes modes. | Cognitive processing time; accessibility; error reduction | Extra time matches cognitive processing speed and supports universal usability, lowering rushed errors. |
| 5.6 Cue statistics can be hard to interpret | Add plain-language hints such as "Aim: extends guideline" or "Time: longer turns" beside each stat. | Recognition rather than recall; mental models; learnability | Visible cues let users recognise each attribute's effect instead of recalling it, improving cue decisions. |
| 5.7 Power meter can cause overpowered shots | Add stronger visual feedback for soft / medium / hard ranges before release. | Feedback; motor accuracy; error prevention | Clearer pre-release feedback makes strength predictable and prevents accidental scratches or poor position. |
| 5.8 Chat and emoji reactions distract during shots | Add a focus mode that hides or delays opponent reactions during the player's turn. | Focused attention; user control | Protecting focused attention and giving users control over distractions reduces mistakes during aiming. |
| 5.9 Reward and event icons are not self-explanatory | Add short labels or first-time tooltips and use consistent metaphors for rewards, events, chests, and offers. | Recognition rather than recall; consistency | Recognisable, consistent icons reduce guessing and stop users opening the wrong menu. |
| 5.10 Menu navigation interrupts the sports experience | Add a "Play Again" path that bypasses non-essential reward and shop screens after a match. | Efficiency; consistent conceptual model; user control | A direct path keeps the conceptual model focused on the sport and lets players continue with fewer interruptions. |

### 7.1 Example Solution Paragraph

Example paragraph based on one of the identified drawbacks:

> One drawback of 8 Ball Pool is that small-screen aiming can be difficult when a user tries to make a precise shot on a phone in a moving or distracting context. In HCI terms this is a **motor system** limitation (dexterity and accuracy) compounded by **Fitts's law**: the exact correct angle is a very small target `S` while the cue ball must travel a long distance `D`, so the index of difficulty `log(D/S + 1)` is high. A practical solution is a precision aiming mode that slows cue rotation during small adjustments, which enlarges the effective target and lowers the index of difficulty. This improves **error prevention** and motor accessibility because the user can aim more accurately, reducing accidental misses and the frustration that lowers **satisfaction**.

### 8. Conclusion

8 Ball Pool provides a generally effective mobile billiards experience because it uses a familiar pool table metaphor, recognizable objects, immediate shot feedback, and touch controls that support quick mobile play. These strengths reduce learning effort and make the core activity understandable for casual, beginner, and competitive players.

However, the analysis also shows that several parts of the interface can create usability problems. Precise aiming, spin, shot power, timers, cue statistics, rewards, and social reactions can increase cognitive load, motor difficulty, or distraction, especially on small screens and in mobile contexts. The most important HCI lesson is that a familiar metaphor is helpful, but it must be supported by clear feedback, accessible controls, simple explanations, and efficient navigation. Improving these areas would make the game easier to learn, less frustrating, and more comfortable for different user types.

### 9. References

- 8 Ball Pool mobile app interface and gameplay observations.
- HCI course materials on usability, feedback, mental models, interaction metaphors, Fitts' Law, cognitive load, and accessibility.
- Nielsen usability heuristics and general usability principles, if allowed by the course.
