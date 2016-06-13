# tween
缓动函数指定动画效果在执行时的速度，使其看起来更加真实。让运动按不动的轨迹速度执行

参数：
start - (optional) Starting value of the tween  开始状态
stop - (required) Final value of the tween 结束状态
time - (optional) Starting time in seconds. Default is 1 second  延迟时间
duration - (optional) Tween duration in seconds. Default is 1 second 持续时间
units - (optional) CSS units to increment in. Default is "px" 动的单位
effect - (optional) Effect to apply to the motion. Default is "linear" 执行效果
onStart - (optional) Callback to trigger when the tween starts 开始回调函数
onFrame - (optional) Callback to trigger after each frame 运动时的回调函数
onStop - (optional) Callback to trigger when the tween stops 结束回调函数
