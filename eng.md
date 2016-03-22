We always knew that ECMAScript 2016 (ES2016) would be a small release. It turns
out that it will be*very* small. Read on for a list of its features and an
explanation why that is not a problem.

 
Any proposals that were at stage 4 on Thursday, 28 January 2016, will be in
ES2016
([source: Brian Terlson][1]). That means that ES2016 will contain just two new
features (in addition to bug fixes and smaller improvements
):

On March 1, a snapshot of [the draft of the ECMA-262 specification][2] will be
made, to start an editing process that finishes with the ratification of ES2016,
probably in June 2016.

### The new release process works {#the-new-release-process-works}

ES2016 being so small demonstrates that [the new release process][3] works:

*   New features are only included after they are completely ready and after
    there were at least two implementations that were sufficiently field-tested.
   
*   Releases happen much more frequently (once a year) and can be more
    incremental.
   

If you are disappointed that your favorite stage 3 feature did not make it into
ES2016 – don’t worry: With[the new release process][3], it’s more about the
stage a proposal is in than what release it is a part of. As soon as a proposal 
reaches stage 4, it is done and safe to use. You’ll still have to check whether 
the JavaScript engines that are relevant to you support the feature, but you 
have to do that with ES6 features, too.

 [1]: https://twitter.com/bterlson/status/692427832555892736
 [2]: https://tc39.github.io/ecma262/
 [3]: http://www.2ality.com/2015/11/tc39-process.html