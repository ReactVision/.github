<p align="center">
  <a href="https://reactvision.xyz">
    <img
      src="https://avatars.githubusercontent.com/u/74572641?s=200&v=4"
      alt="ReactVision"
      width="120"
      height="120"
    />
  </a>
</p>

<h1 align="center">ReactVision</h1>

<p align="center">
  Open-source tools for building spatial, augmented reality, and computer vision experiences with React Native.
</p>

<p align="center">
  <a href="https://reactvision.xyz">Website</a>
  ·
  <a href="https://reactvision.xyz/viro-react">ViroReact</a>
  ·
  <a href="https://studio.reactvision.xyz">ReactVision Studio</a>
  ·
  <a href="https://updates.reactvision.xyz">Blog</a>
  ·
  <a href="https://discord.gg/A6TaFNqwVc">Discord</a>
</p>

---

## Building spatial experiences with React Native

ReactVision develops open-source infrastructure for bringing **augmented reality, spatial computing, and on-device computer vision** to the React Native ecosystem.

Our work is centred around [ViroReact](https://reactvision.xyz/viro-react), providing native integrations and higher-level APIs that make capabilities such as ARKit, ARCore, object detection, face tracking, and spatial rendering accessible from React Native.

We focus on keeping these capabilities:

- **Cross-platform** — targeting iOS and Android from a shared React Native codebase.
- **Native where it matters** — integrating directly with platform APIs and native runtimes.
- **Composable** — specialised capabilities can be added independently instead of bloating the core runtime.
- **On-device** — computer vision workloads can execute locally without requiring a remote inference service.
- **Open source** — our core tooling is available for the community to use, inspect, and improve.

## Projects

### ViroReact

Our core React Native framework for building augmented reality and spatial applications using **ARKit** and **ARCore**.

It provides a declarative React API for scenes, 3D objects, materials, animations, tracking, AR anchors, spatial interaction, and native AR capabilities.

[Explore ViroReact →](https://reactvision.xyz/viro-react)

### `@reactvision/react-viro-onnx`

On-device computer vision for ViroReact using **ONNX Runtime**.

It provides the inference backend for `ViroObjectDetector`, including model execution, non-maximum suppression, class decoding, and hardware-accelerated inference where supported.

[View on GitHub →](https://github.com/ReactVision/react-viro-onnx)

### `@reactvision/react-viro-face-tracking`

Optional front-camera face tracking for ViroReact.

On iOS, it integrates ARKit's TrueDepth face-tracking capabilities while keeping those APIs outside the core ViroReact binary. On Android, ViroReact uses ARCore Augmented Faces.

[View on GitHub →](https://github.com/ReactVision/react-viro-face-tracking)

## ReactVision Studio

**ReactVision Studio** complements the runtime ecosystem with tooling for creating and working with ReactVision experiences.

[Open ReactVision Studio →](https://studio.reactvision.xyz)

## Technology

Our projects sit at the intersection of several technologies:

`React Native` · `TypeScript` · `C++` · `Objective-C++` · `Swift` · `Kotlin` · `ARKit` · `ARCore` · `ONNX Runtime` · `Computer Vision` · `Spatial Computing`

## Community

ReactVision is built in the open.

If you're building with ViroReact, experimenting with spatial computing in React Native, or interested in contributing to the ecosystem, join the community on Discord.

<a href="https://discord.gg/A6TaFNqwVc">
  <img
    src="https://discordapp.com/api/guilds/774471080713781259/widget.png?style=banner2"
    alt="ReactVision Discord"
  />
</a>

## Contributing

Contributions, bug reports, feature proposals, and discussions are welcome.

Individual repositories contain their own development and contribution instructions. For larger proposals, opening a discussion or issue before implementation is recommended.

## Links

- **Website:** https://reactvision.xyz
- **ViroReact:** https://reactvision.xyz/viro-react
- **ReactVision Studio:** https://studio.reactvision.xyz
- **Updates:** https://updates.reactvision.xyz
- **Discord:** https://discord.gg/A6TaFNqwVc
- **npm:** https://www.npmjs.com/org/reactvision

---

<p align="center">
  <strong>ReactVision</strong><br />
  Open-source spatial computing for React Native.
</p>
