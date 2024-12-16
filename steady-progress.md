# How to make steady progress in my research?

[[Link to the original tweet](https://twitter.com/jbhuang0604/status/1419880122006519809)]

I worked so damn hard but "IT JUST DOESN'T WORK!" 
How can I unblock myself quickly and make good progress toward the goals? 

Below I compiled a list of tips that I found useful. 


## Imagine success

Forget about all the technical difficulties for a moment. Imagine you finish your project successfully, would you find the outcome exciting? 

If not, drop the project. Yep, just drop it. Free up your time to work on important problems.

https://user-images.githubusercontent.com/987204/127598836-21f6d798-5722-4361-b322-17397abca8fc.mp4


## Work backward

Say your project involves three steps: A -> B -> C.

First, assume that you have perfect output of B and work on the step C. 

Next, assume that you have perfect output A and work on the step B and so on.

In the end, you will have a fully working method.

Okay, this is weird. WHY?

Because you get to
1) see final outcome early
2) measure the performance upper bound
3) focus on each task with perfect inputs without distraction
4) figure what is needed to achieve the desired results.

https://user-images.githubusercontent.com/987204/127598869-d509e7cb-fd3d-4b00-8c98-f52ea6a0d9a8.mp4

## Toy examples

Design toy examples that capture the essence of your problem. They are sufficiently simple so you can focus on the core problem.

It's also often helpful to construct/synthesize such toy examples so that you have access to all the ground truth in all the steps.

https://user-images.githubusercontent.com/987204/127598916-84c5dab4-40c0-4a96-8597-e9301673bbf0.mp4

## Baseline first

Don't know where to start? Start with trying out baseline methods on your problem.

It helps identify limitations of the state-of-the-art. If they work perfectly well, why do you need to work on this problem? 

Finding specific gaps helps motivate your work.

https://user-images.githubusercontent.com/987204/127598954-9b4d339c-8680-45ed-8eb6-2121420cf9e3.mp4

## Simple case first

If your method does not work on simple/trivial cases, how could you expect it to work on unconstrained, real-world cases?

https://user-images.githubusercontent.com/987204/127598996-8fb68359-dc3a-4654-9714-d7b0c9952db9.mp4

## One thing at a time

When doing experiments, change exactly ONE thing at a time. This helps you understand what the results mean.

https://user-images.githubusercontent.com/987204/127599041-7efa7e30-7872-4128-ab68-ffead74d2935.mp4

## Identify proxy

Do not use full-scale experiments (that may take weeks to complete) as the only way to validate your ideas. Run smaller-scale/simpler experiments with short turnaround time so you get to iteratively refine your ideas a lot faster.

https://user-images.githubusercontent.com/987204/127599091-aa952c0a-970c-476f-963b-358ccf55f6a5.mp4

## Automate everything

If you find that you need to do the same task twice, write a script for that.

Your future self will thank you.

https://user-images.githubusercontent.com/987204/127599125-8689bbda-5c78-4519-b732-12491ac8ef65.mp4


## Visualize everything

You cannot debug what you cannot see. Investing time in visualizing your inputs/intermediate steps/outputs is definitely worthwhile!

https://user-images.githubusercontent.com/987204/127599163-160b670c-4290-4137-8a65-16c769b9975d.mp4


## Quantify success

Instead of always eyeballing a few results on your own, identify a couple of quantitative metrics for your problem and let them guide your exploration.

https://user-images.githubusercontent.com/987204/127599203-96af318a-2026-4d7f-8d98-5ee3494ff20a.mp4

## Make the best use of machine time

Plan your experiments so that your machines still work for you while you are not working.

https://user-images.githubusercontent.com/987204/127599236-f53f245e-f73e-4f61-8ba6-d65c25e7a028.mp4

