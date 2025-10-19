VIROO Studio Template / Assembly Sequence
This template simplifies the process to create training modules focused on Assembly / Dissasembly works in the context of VIROO.

It provides a set of tools based on custom Unity editor Windows / Inspectors, Visual Scripting subsystems, and a collection of prepared prefabs to enable very quick and straight forward creation of interactive collaborative guided content.

How it works:
The main idea is to support the creation of a "Sequence" composed of "Completable Items". In the [Demo] example scene, the sequence is stored in a component named [Completable Sequence Data] in the "SEQUENCE Manager" gameobject present in the Hierarchy.

We provide a set of "Completable Systems" already implemented, but the system is meant to be extended with your own completion systems, which can be implemented in Visual Scripting or in c#

Those "Completable Items" can be of several types including:
  - Audio Completables: Allows to wait for some audio to be played.
  - Video Completables: Wait for a video to be played.
  - Playable Director Completables: Wait for a Playable Director animation to be played.
  - Trigger Completables: Allows for triggers to be enabled by the "Player" or other defined "Tools".
  - Assembly Target Completables: Allows for "Assembly Parts" to be placed on "Assembly Targets" configured with several parameters.
  - Click Completables: Wait for the user to "Click", click can be triggered by a regular mouse, but using a XR controller as well.

For a quick start we recommend:
  1. Running the self explanatory Demo Scene [Assets/Scenes/Demo].
  2. Have a look at our videos and webinars associated to this template.
  3. Explore the "Completion Systems" implemented in Visual Scripting.

To Create / Edit and Configure "Assembly Parts" and "Assembly Targets" we provide a custom editor which [Window/VIROO/Assembly Templates/Assembly Parts Editor]

<img width="1737" height="1257" alt="image" src="https://github.com/user-attachments/assets/d4f32757-bf0e-40de-9fe8-e5c3a23bbe04" />

The full code of the Editor and the Runtime template is part of the project and can be modify if you need to add some extra functionality. You can also contact us if you find something you would like to include in the template to improve it.

We hope you enjoy the template!
