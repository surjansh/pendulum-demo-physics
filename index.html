<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pendulum Swing</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.19.0/matter.min.js"></script>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      overflow: hidden;
      height: 100%;
      background-color: #222;
    }
    canvas {
      display: block;
    }
  </style>
</head>
<body>
  <script>
    const { Engine, Render, Runner, World, Bodies, Constraint } = Matter;

    // Create engine
    const engine = Engine.create();
    const world = engine.world;

    // Set up canvas size
    const width = window.innerWidth;
    const height = window.innerHeight;

    // Create renderer
    const render = Render.create({
      element: document.body,
      engine: engine,
      options: {
        width: width,
        height: height,
        wireframes: false,
        background: '#111'
      }
    });

    // Run the engine and renderer
    Render.run(render);
    const runner = Runner.create();
    Runner.run(runner, engine);

    // Create the pendulum system
    const ball = Bodies.circle(width / 2, height / 4 + 100, 40, {
      restitution: 0.8,
      render: { fillStyle: '#4caf50' }
    });

    const top = Bodies.rectangle(width / 2, height / 4, 120, 20, { isStatic: true, render: { fillStyle: '#222' } });
    const rope = Constraint.create({
      bodyA: top,
      bodyB: ball,
      pointB: { x: 0, y: 0 },
      stiffness: 1,
      length: 200
    });

    // Add to world
    World.add(world, [ball, top, rope]);

    // Add ground
    const ground = Bodies.rectangle(width / 2, height - 50, width, 50, { isStatic: true });
    World.add(world, ground);

    // Adjust gravity if necessary
    world.gravity.y = 1;
  </script>
</body>
</html>
