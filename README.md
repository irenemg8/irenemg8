# Hi, I'm Irene! 👋

🎨 **UX/UI Designer** | 🕹️ **Gamer** | 🚀 **Tech Enthusiast**

Welcome to my GitHub profile! I'm passionate about creating beautiful and functional user experiences. I love blending design with technology to build immersive interfaces. When I'm not designing, you'll find me gaming or tinkering with cool tech stuff.

---

## 🛠️ Skills & Tools

Here are some of the technologies and tools I work with:

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Adobe XD](https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=white)
![Sketch](https://img.shields.io/badge/Sketch-FFB387?style=for-the-badge&logo=sketch&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

---

## 🎮 Games I Love

I'm a huge fan of gaming! Here are some of my favorite games:

![The Witcher 3](https://img.shields.io/badge/The%20Witcher%203-000000?style=for-the-badge&logo=the-witcher&logoColor=white)
![Cyberpunk 2077](https://img.shields.io/badge/Cyberpunk%202077-000000?style=for-the-badge&logo=cyberpunk-2077&logoColor=white)
![Valorant](https://img.shields.io/badge/Valorant-FA4454?style=for-the-badge&logo=valorant&logoColor=white)
![League of Legends](https://img.shields.io/badge/League%20of%20Legends-005A82?style=for-the-badge&logo=league-of-legends&logoColor=white)

---

## 🖼️ 3D Models with Three.js

I love working with 3D models using Three.js. Here's an example of how I integrate 3D into my projects:

```html
<!-- Add your Three.js code here -->
<script type="module">
  import * as THREE from 'https://cdn.jsdelivr.net/npm/three@0.132.2/build/three.module.js';

  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
  const renderer = new THREE.WebGLRenderer();
  renderer.setSize(window.innerWidth, window.innerHeight);
  document.body.appendChild(renderer.domElement);

  const geometry = new THREE.BoxGeometry();
  const material = new THREE.MeshBasicMaterial({ color: 0x00ff00 });
  const cube = new THREE.Mesh(geometry, material);
  scene.add(cube);

  camera.position.z = 5;

  function animate() {
    requestAnimationFrame(animate);
    cube.rotation.x += 0.01;
    cube.rotation.y += 0.01;
    renderer.render(scene, camera);
  }
  animate();
</script>
