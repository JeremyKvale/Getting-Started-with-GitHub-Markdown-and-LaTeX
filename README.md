# Rigid Pendulum Driven by a Pivot Point
This is a repository containing information and responses regarding a rigid pendulum contained by a pivot point that is being driven up and down. Additionally, this repository contains basic Markdown and LaTeX elements.

## How do you expect the rigid pendulum will respond if the frequency of the drive is much higher or much lower than the natural frequency ($\omega_0 = \sqrt{g/L}$) of the pendulum (for small oscillations) and the amplitude is small compared to the size of the pendulum?

In this pendulum problem, the driven pivot point creates a form of **restoring force** that serves to periodically counteract the force of gravity pulling the pendulum down. Thus, having a smaller amplitude generates a smaller restoring force and has a smaller, less stabilizing impact on the pendulum's movement. As for the frequency of the pivot point, there are two main cases: one where the pivot point has a lower frequency than the pendulum's natural frequency, and on where it has a higher frequency.

- For a lower frequency, the pendulum essentially acts independent of the pivot point's movement. This is because the aforementioned restoring force is "in effect" a lot less often, and when it is, it is a lot weaker compared to the pendulum's natural movement.
- For a higher frequency, the pendulum is severely impacted by the pivot point, as the restoring force is in effect much more often and becomes more significant in the overall problem. The pendulum swings faster with smaller amplitude due to the pivot point acting similar to a stronger gravitational force.
- Another case not mentioned in the question is the when the frequency of the pivot point is similar or equal to that of the pendulum's natural movement. When it is similar, the two frequencies **resonate** in a way that results in higher amplitudes for the pendulum.

## If the pendulum is slightly displaced from equilibrium and the pivot point moves down abruptly, what will happen to the pendulum's displacement angle?

If the pendulum's initial angle is displaced some amount and the pivot point moves down simultaneously, this angle will increase slightly. As the pivot point moves abruptly, the end of the pendulum will be unaffected, but the angle between the pendulum and the vertical line (at the point of stable equilibrium: downward) will increase depending on the amplitude of the pivot point.

## If we start the pendulum oriented above its pivot point, at its unstable equilibrium angle, if the pivot point moves down as the pendulum begins to fall, what is your expectation of the behavior? 

In the case that this pendulum system is placed completely vertically and continuously driven, it is described as a *Kapitza Pendulum.* A great video demonstration can be found [here](https://gereshes.com/2019/02/25/kapitzas-pendulum). However, in this case, the pivot point only gives one singular downward pulse. The Kapitza Pendulum functions based on the continuous up and down movement of the pivot point which allows the pendulum to stabilize at this seemingly unstable equilibrium point. For a single downward pulse, the effect will be a small emulation of the Kapitza Pendulum: a slowing effect on the pendulum downward motion. Depending on the frequency of the pulse, the slowing effect will be greater/weaker.

- Lower frequencies (lower than that of the pendulum's natural swinging frequency) will have a very minimal slowing effect.
- Higher frequencies will have a much stronger slowing effect due to the stronger restoring force being applied upward.
