  00:00:01 - Speaker 1
      Okay, we were isolating everything.    The one thing we learned is whether it was this change, whether it was the checkout change that caused the problem.    There is this argument that, you know, by not telling them about the subscription, you're leaving more questions unanswered, meaning that maybe you lower the intent.    I don't know.    I'm with you.    I don't think these changes are causing an issue, but could they be?
  00:00:51 - Michael Michelis (Qalzy)
      So the subscription changes, you mean?
  00:00:52 - Speaker 1
      Certainly.    Probably.
  00:00:57 - Michael Michelis (Qalzy)
      All of them.    I think it's a, yeah, checkout plus.
  00:00:59 - Speaker 1
      All of them apart from the Checkout Plus.    Checkout Plus stays, stays, stays, Unless there's that assumption as well, but it's all assumptions we don't know what we're dealing with here.
  00:01:19 - Michael Michelis (Qalzy)
      Yeah, but you have your intuition.    I mean, but now it has, it makes sense.
  00:01:23 - Speaker 1
      And you have your intuition and it gets, it is wrong so many times, the data show.    It's happening all the time.
  00:01:36 - Michael Michelis (Qalzy)
      Look, still early.
  00:01:36 - Speaker 1
      We don't track for a day without orders at all yet.    Still early, we usually have three, four by this time.    I don't know.    I mean, yeah, I think it's safer.    And then you introduce them on via an AB test.
  00:02:07 - Michael Michelis (Qalzy)
      Too slow, I'm thinking.    Too slow.    What, you're going to wait about five days for this change?    Too slow.
  00:02:23 - Speaker 1
      So now you're going to do what?    Wait for two days and then what?    Hide them afterwards.
  00:02:30 - Michael Michelis (Qalzy)
      Yeah, because if it's the culprit, you've solved all your problems in two days.
  00:02:31 - Speaker 1
      How is that going to be faster?
  00:02:37 - Michael Michelis (Qalzy)
      Otherwise, if you introduce one change every, I don't know.
  00:02:40 - Speaker 1
      What's the culprit?    The culprit is not the changes.    We did these things to improve things.    Because these things were there before and everything was converting.
  00:02:51 - Michael Michelis (Qalzy)
      What thing?    In the checkout class.
  00:02:53 - Speaker 1
      The changes that we did were there before.
  00:02:58 - Michael Michelis (Qalzy)
      Okay.
  00:03:00 - Speaker 1
      Before we changed them, the site was as it was, and it was converting.
  00:03:04 - Michael Michelis (Qalzy)
      Yeah.
  00:03:05 - Speaker 1
      So the reason it's not converting right now, if there is one possibility, like there's two reasons that it might not be converting.    One, because we did the changes.    Two, because there's unqualified traffic.    It can't be anything else.
  00:03:23 - Michael Michelis (Qalzy)
      But if it wasn't...    But the problem with this is the add to cards have stayed the same.    So if your change is affected intent for some reason, the add to cards should have dropped.    So it's more likely that you have unqualified traffic.
  00:03:38 - Speaker 1
      I agree it's more likely that you have unqualified traffic.    I also think that those changes...    Incremental improvements that are irrelevant to solving the current situation.    Because the current situation is solved by fixing the traffic.    If we assume that the problem is the traffic, the current situation is solved by fixing traffic, not by introducing these changes.    So these changes are just introducing noise right now.
  00:04:14 - Michael Michelis (Qalzy)
      But I think we're bundling all the changes in one.
  00:04:14 - Speaker 1
      And increasing your risk without, I agree, it is the most suspicious thing.
  00:04:20 - Michael Michelis (Qalzy)
      That checkout blast was the only thing that couldn't have affected things since it was on the checkout level.
  00:04:32 - Speaker 1
      I mean, there is the other assumption as well, that I'm making about this buffer specifically, because we're saying secure checkout, free returns, but then you were never getting, you were never getting.    Getting charged for them, right?
  00:04:46 - Michael Michelis (Qalzy)
      Thank you.
  00:04:47 - Speaker 1
      So maybe we converted extra because people thought, oh, great, I can buy it and I don't even need to pay for the return.    Awesome.    And then when we fixed it, then that changed things.    And now that we've kind of removed it completely, that changes things as well.    That puts them in a third place, right?    There's the great, I can have free returns and buy it.    There's the great, I can buy it, but without a free return.    And there's, oh, .    There's a free return, I can get a free return, but I need to pay for it.    So there's three different, completely three different states and we can never return to the first one, which was wrong.    So maybe we'll still see a different version, even with the checkout plus issue removed.    You know, and then there's the other argument that says, well, yeah, but we picked that on the Thursday, and on Saturday we had a 2X ROAS day, the button, yeah.
  00:05:51 - Michael Michelis (Qalzy)
      What do we fix on Thursday?    Yeah, yeah, it's a bad class.
  00:05:55 - Speaker 1
      So, you know, there's an argument that it wasn't that.
  00:06:01 - Michael Michelis (Qalzy)
      Also, we could be like, you know, irregularities of this, but that fatigue would not get you, would not, would get you just a CTRX.
  00:06:02 - Speaker 1
      I mean, it all points to our fatigue, all, everything.    Like, that is my top bet right now.
  00:06:22 - Michael Michelis (Qalzy)
      How you explain conversion, people would go there, still see it.    Conversion shouldn't have changed.    I think it's a combination of things.    It's unqualified traffic, that's the only logical explanation.
  00:06:39 - Speaker 1
      I true.
  00:06:40 - Michael Michelis (Qalzy)
      It dropped, but it shouldn't affect convergence.    It should only affect CTR, maybe.
  00:07:06 - Speaker 1
      I had to cart first table.    It's the checkout that  up.    Maybe it's a combination of AdFaDig and Checkout Plus.    Or the fact that there's information on the page that they're missing.    But again, the subscription changes were done after.
  00:07:43 - Michael Michelis (Qalzy)
      And then...
  00:07:43 - Speaker 1
      It was after the drop.    mean, the only thing that we did before the drop was the add-ons.    The add-ons and the extra section with the place press track, which, you know, the only negative effect that it might have had is pushing things further down the page so people not reaching sections that they should have been reaching and would be helpful with conversion.    All of these are hypotheses.    And if we switch back to the original state, then at least we know it was none of these.    are we finding?    Say we leave the changes on it.    What are we going to know?
  00:08:39 - Michael Michelis (Qalzy)
      If it goes back to where it was, we know that it's like a checkout class.
  00:08:45 - Speaker 1
      He died, μ'αλάκα, μου είσαι πας στα αρχίδια μου, παίρνει ότι διαρκώς τηλέφωνο.    Καθώς θέλουν να μου βουλήσουν.    Μ'απαντάει το AI, απλά τώρα έγραμε μ'αλάκα, για να δω ποιος είναι, ξέρω εγώ, και άμα δεις ποιος είναι, αρχίζει και χτυπάει, αλλιώς δεν χτυπάει.    Ναι, άμα όμως δεν βελτιωθεί, που είναι ένα δυνατό σενάριο, δεν ξέρεις αν έφτεγαν τα changes ή αν έφτεγαν τα άλλα.    Thank acquisition, but if you the reverse, if you do the reverse, then know how to do it.    The problem is that if you do the it will be ok.
  00:09:52 - Michael Michelis (Qalzy)
      Lamp.    Δεν θα έχουμε πολλά data, δείξω εδώ αυτό το EBITEST που ήταν Significal, λάβει για price change.    Εξήκη, το έχουμε 3 weeks να τρέχει και δεν έχουμε Significal data.    Τι EBITEST θα τρέξουμε.
  00:10:13 - Speaker 1
      We will try to test one or two weeks, if you the 50-50, we will try to you very much.    We'll tell you that this phase we don't a test, we did full on reverse and if we can't build things, it says it's because it's because of this.    If we don't build things, we'll know what's going on.
  00:10:50 - Michael Michelis (Qalzy)
      Thank you.
  00:10:50 - Speaker 1
      If we move things around and we don't build things, we know what's going on.    And I have time for some logic gap.
  00:11:25 - Michael Michelis (Qalzy)
      Save the traffic.
  00:11:29 - Speaker 1
      The changes in the be by the result of the The most likely scenario is that the results will remain as they were, I think.    If the results will remain as they are, you don't if it's traffic.    You have a problem, then the agency will like, then you'll see the changes in the results.    You don't happening, what's If you don't know what happens to results, then you'll see the to update or to update account.    Because of course, I don't if Facebook is the spending partner or if it's a website or or website.    To the extent that can into changes.    Then can get into the without a test.
  00:12:36 - Michael Michelis (Qalzy)
      It's not a bad thing.    It's a bad thing.    It's not thing.
  00:12:38 - Speaker 1
      I don't think a gangster to do a test.    Every time I do a change in my I say, son of I'm not sure how to a test, I know.    I have a mechanism to make a high page elements.
  00:12:55 - Michael Michelis (Qalzy)
      it's not a bad thing.    You can't hide the add-on, especially when you have 25% of traffic before doing the social proof.    And it's a bad thing that I'm saying that it's bad thing.    But it's like that.    Jeff Bezos said that if the anecdotes don't fit the data, your data is wrong.    So we talking about the mechanism.
  00:13:22 - Speaker 1
      Oh, catcher, catcher, catcher, catcher, anecdotes are experiences, physical experiences.    They are hypothesis and what you can see is hypothesis.
  00:13:31 - Michael Michelis (Qalzy)
      But how do explain it?
  00:13:31 - Speaker 1
      They are anecdotes.
  00:13:32 - Michael Michelis (Qalzy)
      How do you explain it?    Let's talk about the more scientific level.    The Norton says that if you don't the mechanism, and the A-B test and the Randomized Cotone Trial gives you positive results, like the Ingest Collagen, then you believe in the trial, if you don't understand the mechanism.    Because if you don't the mechanism, then you get the add-ons.    How do explain Do you want to ask the general mechanism of the mechanism?
  00:14:02 - Speaker 1
      So I'm not going to get into the data.
  00:14:11 - Michael Michelis (Qalzy)
      If you tell the theory that you're based on, then you'll be based on the data.    But if you don't the theory,    So if you want to explain it, You have to understand understand it.
  00:14:19 - Speaker 1
      Yeah, that's idea.    I don't I don't know.
  00:14:26 - Michael Michelis (Qalzy)
      You have to understand it.    to This is OK.
  00:14:32 - Speaker 1
      I don't we data, the mechanism is that they can see all of this.    It can be free to EOV, the conversion.
  00:14:42 - Michael Michelis (Qalzy)
      If you want to affect the EOV, I understand it.
  00:14:46 - Speaker 1
      15%, 15%?%?    It's a little.
  00:14:49 - Michael Michelis (Qalzy)
      Agree?
  00:14:49 - Speaker 1
      If you look data, it's 15%, it's 15%.    So we're talking about it.
  00:14:53 - Michael Michelis (Qalzy)
      Yes.    But EOV, understand it.
  00:14:54 - Speaker 1
      We're talking about it.
  00:14:55 - Michael Michelis (Qalzy)
      But we are talking about the conversion.
  00:15:01 - Speaker 1
      We're talking about the Yeah, we're talking about conversion.    That's what if we're talking about EOV, and the different hypothesis, one is...    ...    Really?    the solution the time異喜b Ijcola.    103%.    Or maybe you're ake side conversion as you can videos for your business.
  00:15:22 - Michael Michelis (Qalzy)
      Ναι, ναι.
  00:15:23 - Speaker 1
      So follow us on LinkedIn رμ stacked on Twitch.
  00:15:26 - Michael Michelis (Qalzy)
      Ναι, ναι, ναι.    Σε αυτό συμφωνώ.
  00:15:40 - Speaker 1
      Because the first thing that they engage is, what they want them.
  00:15:48 - Michael Michelis (Qalzy)
      Ναι, εντάξει και εμείς ίδιο θα κάνουμε εστάσεις τους.
  00:15:51 - Speaker 1
      I don't it.    I don't think I'm That's right, that's right.
  00:15:56 - Michael Michelis (Qalzy)
      Καλό strategy.
  00:15:59 - Speaker 1
      Okay, that's right.    get something don't know what They change.    And the results, see you.    That's right.    I results of can do and and watch the same I told    Okay, μπορεί να είναι και AdFatigue, αλλά εγώ που δουλεύω σε τόσους accounts και βλέπω AdFatigue σε τόσους accounts, δεν μου μοιάζει με AdFatigue αυτό.
  00:16:12 - Michael Michelis (Qalzy)
      Thank very much, Michael Michelis.
  00:16:18 - Speaker 1
      Μπορεί και να είναι, μπορεί και να κάνω λάθος ρε παιδί μου, αλλά δεν μου μοιάζει.    Best bet.    Remove the changes.    Να είμαστε να κοιμηθούμε και...    Ήσυχα.    Να μην έχεις τύψεις.
  00:16:45 - Michael Michelis (Qalzy)
      Yes, yes, yes, yes, yes.
  00:16:45 - Speaker 1
      Δες θα έκανα μαλακία.    Τώρα θα πάω πειράξει το AdAccount πάλι.    But you see, I have to pay away from the top performing creative and it has to pay to the other top performance creative and the same style.    I have to say that can be the bottom of the funnel creative.    I have to say that the the first time.    That's why started to pay for to the steel, 10-20 liras.
  00:17:42 - Michael Michelis (Qalzy)
      Ναι, αυτοί κλείσανε αυτά που δεν φέρνουνε, όχι αυτά που φέρνουνε.
  00:17:45 - Speaker 1
      Oh, oh, oh, oh, oh, oh, oh, oh.    that's why I started to pay for I started to pay for I started to pay for now.
  00:17:48 - Michael Michelis (Qalzy)
      Γιατί τα κλείσανε.    Νομίζω ότι κλείσανε αυτά που δεν φέρνουνε.
  00:18:04 - Speaker 1
      It doesn't closed, it doesn't been    So we went with Fathom and Fathom it was just asked a question for Fathom and Fathom.
  00:18:06 - Michael Michelis (Qalzy)
      Okay.
  00:18:35 - Speaker 1
      And they said, it friend?    in the creative scheme or in the start of the task.    I'll go ahead and you    28.
  00:19:20 - Michael Michelis (Qalzy)
      So I don't have a question about Fathom.
  00:19:26 - Speaker 1
      Η καταστροφή ξεκίνησε στις 23, λέει εδώ.    Gray Swaps Creatives and Targeting.    Αν και μετά μου είπε ότι δεν έκανε swap τίποτα.    New SPG Adset and 23 new ads 25 Σεπτεμβρίου.    Εδώ μου δείχνει 1,9, 1,2, 1,5 το conversion.    Και στις έκλεισε τα old ads και πέσαμε στο 1,3 και μετά στο 1 την επόμενη μέρα.
  00:20:06 - Michael Michelis (Qalzy)
      In fact, one scenario that I thought about before is that the shoot of Facebook can have embeddings in the page, and I like to have all these things to change the embeddings and not have quality traffic to us.
  00:20:07 - Speaker 1
      Eγώ στις 25 άλλαξα το Scale Guide Copy.    Α, τι σχέση έχει το Scale Guide Copy.    Την Παρασκευή έγινε.    Ναι, 23.    For Laptacreders, who said they had reviews, but not they had a test of Ramanos.
  00:21:05 - Michael Michelis (Qalzy)
      For example, we got the Addons, we changed the signature that have on Facebook for landing page.    Random theories.    Yeah, I don't know if take deep-by-days these spend, I don't want don't know.
  00:21:58 - Speaker 1
      26.00.    Είχαμε 1.82 CPA.    23.00..88.00.    Αυτά ήταν τα καλύτερα CPS που πήραμε.    23.00 προηγούμενη Τετάρτη και το Σάββατο 26.00.    Είχαμε ένα DEAP Τετάρτη Παρασκευή και μετά από Κυριακή και μετά το χάος.
  00:22:42 - Michael Michelis (Qalzy)
      Yeah.
  00:22:45 - Speaker 1
      Φίλοι, έχει παίξει η κατάρρευση, όμως.
  00:22:50 - Michael Michelis (Qalzy)
      Yeah.    Yeah, if you have brought the anomaly to Sabbat, you can think that the crisis started more than before.
  00:22:58 - Speaker 1
      If you could think that, yes, it anomaly, I agree.    If you see the greatest climate, it will very much.
  00:23:02 - Michael Michelis (Qalzy)
      That's what I'm That's we started the anomaly to Sabbat.
  00:23:29 - Speaker 1
      And on December 21st, 1,6% will be, not so much.    Thank you.    Tίποτα, είχαμε απλά μια καλή εβδομάδα μας σε Σεπτέμβριο, κατά τα άλλα το CPA είναι πάνω κάτι το ίδιο.    Εντάξει, όχι, 14-15, ναι, εκεί είχαμε πέσει στα κατοστάρικα, ξέρω, και χαιρόμασταν.
  00:24:24 - Michael Michelis (Qalzy)
      The 21st of the ROAS is 1,13.    After a good day, it's Friday, Friday, Friday, Friday, Friday, Friday.    On the other hand, were talking 10.000 impressions, so we were talking about 10 day.
  00:25:56 - Speaker 1
      Σήμερα είχαμε ένα peak στη μέση του μήνα και ξανά πέσε.    Το CPZ έχει πέσει, σταθερά πέφτει στο account και το CPM έχει σταθερή πτώση.
  00:26:39 - Michael Michelis (Qalzy)
      Thank you.
  00:27:05 - Speaker 1
      So after that, the 28th and then, it was a catastrophe.    We had to through the new law.
  00:27:38 - Michael Michelis (Qalzy)
      Ναι, λοιπόν, είναι τα addons, τα FAQs, το Play's Press Track έξω, το The Sleekest Section, και Bring Back the Premium Comparations έξω.
  00:27:41 - Speaker 1
      What's your name, Fathom?    Eγώ σου λέω γυρνατά να τελειώσουμε, να ξεπερδέψουμε αυτή την κοιβέτα, ξέρω τουλάχιστον, να σου πούμε έχουν αλλάξει και τα locations, έχουν αλλάξει και γιατί πράγματα.    Την ξέρω να αξίζει να κάνουμε reverse.
  00:28:17 - Michael Michelis (Qalzy)
      Έχω κάνει πάρυλα changes και έχω φτιάξει και backs, οπότε μην δίσκομαι.    Θα αρέσει να αφήσω όλα αυτά.    Αυτά είναι τα παίξοντερα.
  00:28:35 - Speaker 1
      To place press track φεύγει και το discoverer free art φεύγει, σωστά, φωτόδομ ξεκίνησε να πέφτει το performance.
  00:28:37 - Michael Michelis (Qalzy)
      Yeah?    Yes.    And then we'll leave We'll do it this.    We'll it after it this.    We'll do it this.    Okay.
  00:29:04 - Speaker 1
      Τι θα δεις, δηλαδή άμα δεις που ήταν η σελίδα πιο πριν δεν το όχι αυτό, την καλή μας εβδομάδα δεν το όχι αυτό.
  00:29:23 - Michael Michelis (Qalzy)
      We'll leave it with indicators, so I won't have to leave this.
  00:29:30 - Speaker 1
      Thank you much.
  00:29:32 - Michael Michelis (Qalzy)
      No, hide through, hide for us.    All the changes we have on the product page.    I will try to fix all of these things and I will try fix all these things.    No, no, order.
  00:30:30 - Speaker 1
      Antromeda, Facebook, the same.    Laceony, and it's 194, and it's got to be discount, is it a hard time?
  00:30:43 - Michael Michelis (Qalzy)
      How are Can't not change this whole share.
  00:30:58 - Speaker 1
      Yes, it's 54, I think I've to do order, ok, it's it's done.

