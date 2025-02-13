[//]: # (title: Participate in the Kotlin Early Access Preview)

You can participate in the Kotlin Early Access Preview (EAP) to try out the latest Kotlin features before they are released.

We ship a few Beta (_Beta_) and Release Candidate (_RC_) builds before every feature (_1.x_) and incremental (_1.x.y_) release. 

We'll be very thankful if you find and report bugs to our issue tracker [YouTrack](https://kotl.in/issue). 
It is very likely that we'll be able to fix them before the final release, which means you won't need to wait until the next Kotlin release for your issues to be addressed. 

By participating in the Early Access Preview and reporting bugs, you contribute to Kotlin and help us make it better 
for everyone in [the growing Kotlin community](https://kotlinlang.org/community/). We appreciate your help a lot! 

If you have any questions and want to participate in discussions, you are welcome to join the [#eap channel in Kotlin Slack](https://app.slack.com/client/T09229ZC6/C0KLZSCHF). 
In this channel, you can also get notifications about new EAP builds.

**[Install the Kotlin EAP Plugin for IDEA or Android Studio](install-eap-plugin.md)**

> By participating in the EAP, you expressly acknowledge that the EAP version may not be reliable, may not work as intended, and may contain errors.
>
> Please note that we don't provide any guarantees of compatibility between EAP and final versions of the same release. 
>
{type="note"}

If you have already installed the EAP version and want to work on projects that were created previously, 
check [our instructions on how to configure your build to support this version](configure-build-for-eap.md). 

## How the EAP can help you be more productive with Kotlin

* **Prepare for the Stable release**. If you work on a complex multimodule project, participating in the EAP may streamline your experience when you adopt the Stable release version. The sooner you update to the Stable version, the sooner you can take advantage of its performance improvements and new language features. 

  The migration of huge and complex projects might take a while, not only because of their size, but also because some specific use cases may not have been covered by the Kotlin team yet. By participating in the EAP and continuously testing new versions of Kotlin, you can provide us with early feedback about your specific use cases. This will help us address as many issues as possible and ensure you can safely update to the Stable version when it's released. [Check out how Slack benefits from testing Android, Kotlin, and Gradle pre-release versions](https://slack.engineering/shadow-jobs/).
* **Keep your library up-to-date**. If you're a library author, updating to the new Kotlin version is extremely important. Using older versions could block your users from updating Kotlin in their projects. Working with EAP versions allows you to support the latest Kotlin versions in your library almost immediately with the Stable release, which makes your users happier and your library more popular.
* **Share the experience**. If you're a Kotlin enthusiast and enjoy contributing to the Kotlin ecosystem by creating educational content, trying new features in the Kotlin EAP allows you to be among the first to share the experience of using the new cool features with the community.

## Build details

<!-- _No preview versions are currently available._ -->

<table>
    <tr>
        <th>Build info</th>
        <th>Build highlights</th>
    </tr>
    <tr>
        <td><strong>1.9.20-RC2</strong>
            <p>Released: <strong>October 24, 2023</strong></p>
            <p><a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-RC2" target="_blank">Release on GitHub</a></p>
        </td>
        <td>
             <ul>
                 <li>K2: support for Kotlin/Wasm, preview kapt compiler plugin</li>
                 <li>Kotlin/JVM: support for Java 21 bytecode</li>
                 <li>Kotlin/Native: custom allocator enabled by default, full parallel mark available in the GC, deprecated targets disabled, obligatory opt-in for all cinterop declarations (except for platform libraries), the GC scheduler tracking objects in big chunks, legacy memory manager disabled, support for Xcode 15</li>
                 <li>Kotlin Multiplatform: hierarchy template available by default, full support for Gradle Configuration cache, the default support for third-party cinterop libraries, reworked configuration of compiler settings in multiplatform projects</li>
                 <li>Kotlin/Wasm: support for WASI, new <code>wasm-wasi</code> target and rename <code>wasm</code> target to <code>wasm-js</code>, compatible with recent updates in Wasm GC</li>
                 <li>Kotlin/JS: using open-addressing hash map in the JS stdlib, ability to generate one JS file for each Kotlin source file</li>
                 <li>Libraries: experimental support for <code>enumEntries()</code> function, further stabilization of Kotlin/Native standard library</li>
                 <li>Gradle: support for Gradle versions 8.0 and 8.1, new build metrics for Kotlin/Native tasks, support for test fixtures to access internal declarations, new property to configure custom path to Konan and its dependencies</li>
            </ul>
            <p>For more details, please refer to the <a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-RC2">changelog</a> or <a href="whatsnew-eap.md">What's new in Kotlin 1.9.20-RC2</a>.</p>
        </td>
    </tr>
    <tr>
        <td><strong>1.9.20-RC</strong>
            <p>Released: <strong>October 12, 2023</strong></p>
            <p><a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-RC" target="_blank">Release on GitHub</a></p>
        </td>
        <td>
             <ul>
                 <li>K2: support for Kotlin/Wasm, preview kapt compiler plugin</li>
                 <li>Kotlin/JVM: support for Java 21 bytecode</li>
                 <li>Kotlin/Native: custom allocator enabled by default, full parallel mark available in the GC, deprecated targets disabled, obligatory opt-in for all cinterop declarations (except for platform libraries), the GC scheduler tracking objects in big chunks, legacy memory manager disabled, support for Xcode 15</li>
                 <li>Kotlin Multiplatform: hierarchy template available by default, full support for Gradle Configuration cache, the default support for third-party cinterop libraries, reworked configuration of compiler settings in multiplatform projects</li>
                 <li>Kotlin/Wasm: support for WASI, new <code>wasm-wasi</code> target and rename <code>wasm</code> target to <code>wasm-js</code>, compatible with recent updates in Wasm GC</li>
                 <li>Kotlin/JS: using open-addressing hash map in the JS stdlib, ability to generate one JS file for each Kotlin source file</li>
                 <li>Libraries: experimental support for <code>enumEntries()</code> function, further stabilization of Kotlin/Native standard library</li>
                 <li>Gradle: support for Gradle versions 8.0 and 8.1, new build metrics for Kotlin/Native tasks, support for test fixtures to access internal declarations, new property to configure custom path to Konan and its dependencies</li>
            </ul>
            <p>For more details, please refer to the <a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-RC">changelog</a> or <a href="whatsnew-eap.md">What's new in Kotlin 1.9.20-RC</a>.</p>
        </td>
    </tr>
    <tr>
        <td><strong>1.9.20-Beta2</strong>
            <p>Released: <strong>September 21, 2023</strong></p>
            <p><a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-Beta2" target="_blank">Release on GitHub</a></p>
        </td>
        <td>
             <ul>
                 <li>Kotlin/JVM: support for Java 21 bytecode</li>
                 <li>Kotlin/Native: custom allocator enabled by default, full parallel mark available in the GC, deprecated targets disabled, obligatory opt-in for all cinterop declarations (except for platform libraries), the GC scheduler tracking objects in big chunks, legacy memory manager disabled</li>
                 <li>Kotlin Multiplatform: hierarchy template available by default, full support for Gradle Configuration cache, the default support for third-party cinterop libraries, reworked configuration of compiler settings in multiplatform projects</li>
                 <li>Kotlin/Wasm: support for WASI, new <code>wasm-wasi</code> target and rename <code>wasm</code> target to <code>wasm-js</code>, compatible with recent updates in Wasm GC</li>
                 <li>Kotlin/JS: using open-addressing hash map in the JS stdlib, ability to generate one JS file for each Kotlin source file</li>
                 <li>Libraries: experimental support for <code>enumEntries()</code> function, further stabilization of Kotlin/Native standard library</li>
                 <li>Gradle: support for Gradle versions 8.0 and 8.1, new build metrics for Kotlin/Native tasks, support for test fixtures to access internal declarations, new property to configure custom path to Konan and its dependencies</li>
            </ul>
            <p>For more details, please refer to the <a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-Beta2">changelog</a> or <a href="whatsnew-eap.md">What's new in Kotlin 1.9.20-Beta2</a>.</p>
        </td>
    </tr>
    <tr>
        <td><strong>1.9.20-Beta</strong>
            <p>Released: <strong>September 11, 2023</strong></p>
            <p><a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-Beta" target="_blank">Release on GitHub</a></p>
        </td>
        <td>
             <ul>
                 <li>Kotlin/JVM: support for Java 21 bytecode</li>
                 <li>Kotlin/Native: custom allocator enabled by default, full parallel mark available in the GC, deprecated targets disabled, obligatory opt-in for all cinterop declarations (except for platform libraries), the GC scheduler tracking objects in big chunks, legacy memory manager disabled</li>
                 <li>Kotlin Multiplatform: hierarchy template available by default, full support for Gradle Configuration cache, the default support for third-party cinterop libraries, reworked configuration of compiler settings in multiplatform projects</li>
                 <li>Kotlin/Wasm: support for WASI, new <code>wasm-wasi</code> target and rename <code>wasm</code> target to <code>wasm-js</code>, compatible with recent updates in Wasm GC</li>
                 <li>Kotlin/JS: using open-addressing hash map in the JS stdlib, ability to generate one JS file for each Kotlin source file</li>
                 <li>Libraries: experimental support for <code>enumEntries()</code> function, further stabilization of Kotlin/Native standard library</li>
                 <li>Gradle: support for Gradle versions 8.0 and 8.1, new build metrics for Kotlin/Native tasks, support for test fixtures to access internal declarations, new property to configure custom path to Konan and its dependencies</li>
            </ul>
            <p>For more details, please refer to the <a href="https://github.com/JetBrains/kotlin/releases/tag/v1.9.20-Beta">changelog</a> or <a href="whatsnew-eap.md">What's new in Kotlin 1.9.20-Beta</a>.</p>
        </td>
    </tr>
</table>

> If the Kotlin EAP plugin can't find the latest EAP build, check that you are using the latest version of [IntelliJ IDEA](https://www.jetbrains.com/help/idea/update.html) or [Android Studio](https://developer.android.com/studio/intro/update).
>
{type="note"}