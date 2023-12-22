# Bouncing Objects in Godot

#godot #gamedev #physics

## 2D

Vector2 includes a function called Vector2.bounce(normal: Vector2) that works wonders for bounces were the inbound angle should equal the outbound angle.

I used it to great effect in my [[Creating Pong in Godot|Pong]] game - it is a very simple use case however. To get the collision normal, I return the collision info from [PhysicsObject2D.move_and_collide](https://docs.godotengine.org/en/stable/classes/class_physicsbody2d.html#class-physicsbody2d-method-move-and-collide) and then retrieve the normal using [KinematicCollision2D.get_normal](https://docs.godotengine.org/en/stable/classes/class_kinematiccollision2d.html#class-kinematiccollision2d-method-get-normal).

```gdscript
# I think this was it
func process():
	var collision = move_and_collide(_velocity)
	if (collision):
		_velocity = _velocity.bounce(collision.get_normal())
```