[mirai-core](../../index.md) / [net.mamoe.mirai.event](../index.md) / [kotlinx.coroutines.CoroutineScope](index.md) / [subscribeTempMessages](./subscribe-temp-messages.md)

# subscribeTempMessages

`fun <R> CoroutineScope.subscribeTempMessages(coroutineContext: `[`CoroutineContext`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html)` = EmptyCoroutineContext, concurrencyKind: ConcurrencyKind = Listener.ConcurrencyKind.CONCURRENT, priority: EventPriority = EventPriority.MONITOR, listeners: `[`TempMessageSubscribersBuilder`](../-temp-message-subscribers-builder.md)`.() -> R): R`

订阅来自所有 [Bot](../../net.mamoe.mirai/-bot/index.md) 的所有临时会话消息事件

**See Also**

[subscribe](subscribe.md)

[CoroutineScope.incoming](incoming.md)

