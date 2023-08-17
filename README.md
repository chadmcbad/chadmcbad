javascript:(async()=>{Object.values(document.querySelector('body div[class*="camelCase"]'))[1].children[0]._owner.stateNode.state.game.scene.physics.world.bodies.entries.forEach(e=>e?.gameObject?.receiveDamage?.(e.gameObject.hp,1))})();

