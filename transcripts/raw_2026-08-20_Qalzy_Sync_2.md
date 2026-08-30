  00:00:03 - Speaker 1
      Okay.
  00:00:09 - Michael Michelis (Qalzy)
      Ναι, για να τα κάνουμε κορεύτερα τα categories, εδώ έχει η ολοκροπράγνωμα.    Δεν είναι απλά λάζεις τα database.
  00:00:15 - Speaker 1
      Ναι, ναι, αυτό σχέσαμε κι εγώ και πες να γίνουν περισσότερες μαλακίες και να ασχολούμαστε με αυτό για πάντα.
  00:00:22 - Michael Michelis (Qalzy)
      7 step plan μου έχει βγάλει και να αλλάξει ένα category.
  00:00:26 - Speaker 1
      Ναι, ναι, ναι, θυμάμαι ότι δεν είναι τόσο απλό.    Φιλιαίτερα, περνάμε τίποτα info στο Google για αυτά τα categories.
  00:00:41 - Michael Michelis (Qalzy)
      Έχω call, έχω call, και έχω στο κέδιο, κοίταξε, τα υπηρεία τους φαμόσαμε.
  00:00:48 - Speaker 1
      Περνάμε τίποτα info σε αυτά τα categories.    Περνάμε τίποτα info στο Google για ποιο είναι το original category.    να περνάμε στο LLM του Google.
  00:00:57 - Michael Michelis (Qalzy)
      Ναι, ναι, περνάει.    Δεν ξέρω για το Google.    Κάτσα με το σου.
  00:01:07 - Speaker 1
      Επίσης ήταν και λεφτά να το κάνουμε, να μην τους αρέσει, να τα ξανατρέξουμε, θα είναι λεφτά, σοβαρά, είναι λεφτά.
  00:01:18 - Michael Michelis (Qalzy)
      Λογική δεν θα περνάμε, γιατί να μην είναι λάθος ότι το περάσεις.    Δεν πιάζει νόημα ότι το περάσεις.
  00:01:34 - Speaker 1
      Τότε μπορούμε να πούμε, look, your categories are generally inaccurate, we have a conversation, we use AI to identify the correct categories, that has significantly improved accuracy.    There will be a small subset, small subset of products that, you know, have their own number, their own category.    If you prefer, we can completely remove the products where our AI disagrees with your category.    Αν και θυμάμαι ο Ρόγκα να λέει ότι δεν είναι τόσο απλό να κάνεις remove products.
  00:02:10 - Michael Michelis (Qalzy)
      Ναι.
  00:02:15 - Speaker 1
      Θα ξαναμπαίνουνε και θα πάει να το...
  00:02:17 - Michael Michelis (Qalzy)
      Το δέμα είναι ότι άμα τα κάνεις remove, πρέπει κάπως μετά τα jobs να τα κάνουν skip αυτά τα products.    Δεν θα είναι τόσο απλό.    Ναι.
  00:02:36 - Speaker 1
      Θα μπορούσες να κάνεις update το category αυτών των products που διαφωνούνε με το category το δικό του.
  00:02:45 - Michael Michelis (Qalzy)
      Ε, ναι.    Απλά δεν θα είναι απλό αυτό.
  00:02:48 - Speaker 1
      Όντως.
  00:02:50 - Michael Michelis (Qalzy)
      Σου λέω 7 step projects.    Πώς είναι αυτό.    Πρώτα πρέπει να αποφασίσεις source of truth.    Μετά να γράψεις τα categories.    Μετά να κάνεις rebuild όλα τα category dependent labels.    Να κάνεις clear και regenerate similar.    Clear and generate outfits.    Stop the pipeline putting the wrong category and then sanity check.    Τι με είχε ξεχάσει αυτό που...
  00:03:30 - Speaker 1
      Αυτό το πρώτο πρόβλημα που είχαμε το βρήκαμε.
  00:03:37 - Michael Michelis (Qalzy)
      Ένα hard code, it's all about this.    Ευχαριστώ.    Υπότιτλοι AUTHORWAVE Υπότιτλοι AUTHORWAVE Υπότιτλοι AUTHORWAVE
  00:03:52 - Speaker 1
      Θα πούμε να κάνουμε push-back.    Κι αυτή ξέρεις είναι αυτό που φτιάζεται ψηδίζει.    We roll back.    We cannot have this experience.    Και όμως αρχικά μας μαθήσουμε να κάνουμε push-back και ας πούμε ότι, Look, your categories are generally a lot worse.    We've tried this before.    We do not recommend using them.    All AIs have a small number of mistakes.    Τι πόσο στα.    5% we disagree.    Ευχαριστώ.    Ευχαριστώ.    Θα φτάνουμε στραίτηση.    Σε φάση, sorry, there are some cases where it's be a product and there's gonna be some outliers.
  00:05:06 - Michael Michelis (Qalzy)
      Λωτρά την πορεμότητα, it's not Google Cloud Vision, it's IntelliStyle's Clip Classifier.    Έτσι λέει.
  00:05:15 - Speaker 1
      Όντως.    Μήπως και πει ο Γιώργος σε κάποια φάση το έχουμε δοκιμάσει και το Google δεν έχει ρόβερα Ριζόλτους και στα δάδια πιο LLM χρησιμοποίηση.
  00:05:25 - Michael Michelis (Qalzy)
      Κάτι μου θυμίζει, ναι.    Μου φαίνεται τρελό ότι το δικό μας μοντέλο είναι καλύτερο από τα τελευταία ελέγματα.    Μπορούμε να είναι ακριβά από τα τελευταία ελέγματα.
  00:05:44 - Speaker 1
      Interesting.    So, it's our model.
  00:05:49 - Michael Michelis (Qalzy)
      Ναι, και «Along with the first image, it can take product title, product description, remote product category, we do not send the mapped field category».    Έτσι φαίνεται.
  00:06:06 - Speaker 1
      Αν δίνουμε product, δίνουμε description, αλλά δεν δίνουμε αυτό που μας είπαν αυτοί ότι είναι το προϊόντο.    Για να μην το περιδέξουμε.
  00:06:13 - Michael Michelis (Qalzy)
      Ναι, έτσι φαίνεται.    Και τι κεντήσουμε, αφού ξέρουμε ότι απλά έβγαλε λάθος αποτέλεσμα.
  00:06:22 - Speaker 1
      Θα μπορούσαμε να το τρέξουμε για ένα προϊόν που ξέρουμε ότι είναι λάθος.    Το clip model.    Μήπως υπάρχει κάποιο πρόβλημα με τα data, εγώ σκέφτομαι.    Δεν ξέρω.    Κάποιον back παίζει αυτό.
  00:06:44 - Michael Michelis (Qalzy)
      Ωραία.    Νομίζω απλά το απλήκε λάθος.
  00:06:48 - Speaker 1
      Γιατί είναι παλιό μοντέλο αυτό.    Τρέχει για καιρό, τρέχει για διάφορους πελάτες.    Θα έχουνε κανένα description περίεργο αυτή που θα λέει styling with this ή κανέναν τέτοιο περίεργο στο description και θα μπερδεύεται.
  00:07:03 - Michael Michelis (Qalzy)
      Μωρή.    Αλλά βεβαίως δεν έχει description αυτά τα δύο που κοιτάω.    Λέει δεν έχουν, έχουν empty descriptions.
  00:07:15 - Speaker 1
      Ίσως αυτό είναι το πρόβλημα.    Έχουν titles.
  00:07:21 - Michael Michelis (Qalzy)
      Ναι.    Τα titles φαίνονται...    Όσο φαίνεται...    Λέει, the fit category was genes and the vision model stored...    Καλά, βασικά, άμα δεις το πρώτο example, βλέπεις το Hero Image.    Πιο πολύ φαίνεται το top, παρά το Gene.
  00:07:46 - Speaker 1
      Κάτσε λίγο γιατί έχει εκεί, ο καθένας κοιτάει και η δηλίτσα του και λέει «Ο, μάλλον τελευταία, κοφόρικ».
  00:08:14 - Michael Michelis (Qalzy)
      Μέχρι πότε το έχουμε τον Gersmer το Δεκέμβριο.
  00:08:20 - Speaker 1
      Αλλά αυτοί για να κάνουν τόση δουλειά, για να το κάνουν οι πλεμμένες τώρα πρέπει να μείνουν για παραπάνω.    Το πρώτο είναι printed t-shirts, men talks.    Εντάξει, it's not the end of the world, φίλε.    These are AI generated.    Και το δεύτερο είναι Slim Angels.    Και εκεί δεν έχει βγάλει όλα λάθος.    Το έχει περάσει για top.
  00:08:56 - Michael Michelis (Qalzy)
      Ναι.
  00:08:58 - Speaker 1
      Αυτό είναι major miss.    Έχει περάσει αυτό για κάτι άλλο που δεν είναι genes, που είχαν εντύπωση.    Αυτό το ACQ4 το έχει περάσει για top.    Ναι, γιατί το categories, ναι ρε, αυτοί έχουν κάνει κάτι wide categories, men, genes, ξέρω, και δεν ήξεσαν να είναι τράγουσες γιατί είναι.    Αλλά μου έκανε μια εντύπωση που έχει κάνει λάθος το AI σε αυτή τη φωτογραφία.    Θα είναι τα πλή.
  00:09:54 - Michael Michelis (Qalzy)
      Έχει σκάνει μαλακίες το AI.    Εδώ χθες το Hermes, το Gemini 3.1 Pro, πει για να κάνει delete το .10 φάιλ του.    Δεν τα καταστροφή εδώ μου λέξει, έτσι.    Δεν βγάλω και όλα.    Λέω τι κάνεις.    Α, sorry μου λέει.    You were right.    It would be devastating to our setup.    Ότι να.
  00:10:15 - Speaker 1
      Nuclear pattern.
  00:10:17 - Michael Michelis (Qalzy)
      Σε φάς.
  00:10:18 - Speaker 1
      You are right.    Wipe out humanity.    It's my mistake.
  00:10:21 - Michael Michelis (Qalzy)
      Ήταν crazy mistake.    Remove our effort and don't.    Τι κάνεις.    Ναι, ποιο.
  00:10:39 - Speaker 1
      Αυτό το προϊόν, δηλαδή, το έστει και η φόρτα τσέκαρες, έχει λάθος κάτεγκορή.
  00:10:44 - Michael Michelis (Qalzy)
      Τα τρία πρώτα, ένα, δύο, τρία, τις δύο πρωτογραφίες είναι όλα, ναι, λάθος, η predicted, έχει και το prediction score δίπλα δηλαδή.    Αυτό που μου ούστη λες, ποιο είναι αυτό που μου ούστη λες?
  00:11:58 - Speaker 1
      Είναι από την πρώτη φωτογραφία το δεύτερο προϊόν.
  00:12:01 - Michael Michelis (Qalzy)
      Σ' αυτό το feed τους βγάζει jeans, ποιο?
  00:12:04 - Speaker 1
      Α, όχι, αυτό είναι το πρώτο προϊόν.    Στον το πρώτο προϊόν που σου στείλα, τα έχουμε γραμβάλει ανάποδα.    Αυτό είναι το δεύτερο προϊόν.
  00:12:16 - Michael Michelis (Qalzy)
      Αυτό που μου ούστη λες, έχουν jeans κι αυτοί έχουν jeans.
  00:12:20 - Speaker 1
      Τι όμως.
  00:12:22 - Michael Michelis (Qalzy)
      Το jeans που έχουμε εμείς είναι jeans, skinny jeans, ναι.
  00:12:25 - Speaker 1
      Στην παντελόνη, ναι, οπότε δεν μπορείς να καταλάβεις, γιατί αυτοί έχουν μια φωτογραφία η οποία έχει τα πάντα αλλά και κοίτα το δεύτερο, αυτό που ζούστηλα, το 2CRB.
  00:12:40 - Michael Michelis (Qalzy)
      Αυτό το 2CRB είναι speed, αλλά predictive tops, εμείς.
  00:12:49 - Speaker 1
      Αυτό είναι major, εμείς.    Πώς κάνουμε πρεντίκτοπ αυτή τη φωτογραφία, δεν ξέρω.
  00:12:58 - Michael Michelis (Qalzy)
      Ναι, αλλά, άτσι, είναι alt-shot.    Δεν χρησιμοποίησαμε το product image, λες αυτό, χρησιμοποίησαμε το alt-one.    Οπότε αυτό που βλέπεις εσύ, το alternative shot, λέει.
  00:13:09 - Speaker 1
      Το, αααα, γιατί χρησιμοποίησαμε το Alternative Show.
  00:13:19 - Michael Michelis (Qalzy)
      Σε αυτούς κάποιους κανόνας θα είναι που θα πεις, δεν κάνει απλά ή σε όλα.
  00:13:32 - Speaker 1
      Γι' αυτό το λέω, γιατί μπορούμε να τους πούμε look, γιατί θυμάμαι σε κάποια πάση να μας λένε ποιες φωτογραφίες να χρησιμοποιήσουμε.    Μας στείλαν αυτή τη φωτογραφία, αυτή η φωτογραφία είναι για τον πούτσιο, it's your problem, it's your data.    Αυτό θα ήταν πολύ βολικό.    Και εξηγεί και τα πράγματα, γιατί δεν μπορεί εμείς να βγάλαμε από αυτή τη φωτογραφία να βγάλαμε τόν, με τίποτα.    που έπτιαχνα εγώ πριν πάνω το ρόγκα του κανέναν.    Βέζει κάποια αρτογραφία.
  00:14:26 - Michael Michelis (Qalzy)
      Όχι σκύλαξε κατάφεσαι, φαντάζεσαι να μην είχαμε δει «Αι, τώρα κάτσεις έτσι να ψάξεις όλο αυτό».    Ποντέ, τρεις μέρες θα ήθελες.
  00:14:43 - Speaker 1
      Τίποτα με λάγα, καιρός μας το ρίτο εξεινόταν επίσης να βγάλουμε τα κλειδιά του ακόμα παντού.    Δεν ξέρουμε πως αρχίσουμε ότι τα βγάζουμε εσύ, εσύ.
  00:14:52 - Michael Michelis (Qalzy)
      Ποιος ο λόγος, δεν ξέρω μεγάλα σας.    Ποιο ρίσκο είναι να το αργάλουμε παρά να το αφήσουμε.
  00:15:03 - Speaker 1
      Εδώ δεν τούλευε τον καλόκαιρο λέει.    Ε, ξέρεις μη του χαρκάρει κανένα στον υπολογιστή και μετά μας χαρκάρει το σερβερ.
  00:15:12 - Michael Michelis (Qalzy)
      Κάρει κάποιος στην πολιτιστική, ε.
  00:15:16 - Speaker 1
      Ε, δεν είναι τόσο extreme.
  00:15:18 - Michael Michelis (Qalzy)
      Προσθέτει πάλι στο μάτι, δεν πάει κάποιος το ράντομο.    Θα μπεις εσένα το λογιστή και τί θα σκεφτήσεις κάτι στον άτομο που που λέει SSH Access αυτός.    Όχι, θα πάτε το bank accounts, άμα είναι ράντομο το χάκι.    We used it on purpose, λέει.    Να, κοίταξε, χρησιμοπήσαμε αυτό το image.    Τότε και εγώ τέλω λίγο ένα ρογιστή.
  00:15:50 - Speaker 1
      Το purpose ποιο είναι, ναι, ok.    Το purpose ποιο είναι, δεν μας λέει.    Τι λέει, το if, τι λέει εκεί στον κώδικα.    Στην Ελήθεια.
  00:16:13 - Michael Michelis (Qalzy)
      STL needs...    Μάλω, πια μπέζει να έχει γίνει...    So, STL needs the full body look.    Maybe that's why we'll do something.    The bag is that garment category used the STL image instead of the pack shirt or the fit category jeans.    Εμείς χρησιμοποιούμε αυτοί γιατί κάναμε μόνο STL για αυτούς και το αφήσαμε και χρησιμοποιήθηκε και για σύμιμα τους.
  00:16:55 - Speaker 1
      Και...    Φίξαμε.
  00:16:59 - Michael Michelis (Qalzy)
      Κι εγώ έτσι πιστεύω.    Fix it.    Make no mistakes.
  00:17:02 - Speaker 1
      Άρα...    Πρέπει να...    Σίγουρα σε κάποια φάση έχει γίνει μια κουβέντα για το ποιες εικόνες πρέπει χρησιμοποιούμε.
  00:17:12 - Michael Michelis (Qalzy)
      Ναι, αυτό.    Αλλά ήταν για το STL είναι αυτό.
  00:17:14 - Speaker 1
      Υπάρχει αυτό στο κρότικα.
  00:17:18 - Michael Michelis (Qalzy)
      Σου λέει ότι για το STL κριαζόμαστε full body image, οπότε χρησιμοποιήσαμε το alt one.    The bug is, το λέει κιόλας, the bug is that the garment category used the STL image instead of the pack shot.
  00:17:31 - Speaker 1
      Do we know what the fact shot is?    Αυτό το image.
  00:17:33 - Michael Michelis (Qalzy)
      Το πρώτο image, φαντάζομαι.    Α, ναι, δεν παίζει.
  00:17:40 - Speaker 1
      Δεν ξέρω, γιατί το discussion...    Είχαμε με αυτού σε ένα discussion.    Άντε τώρα να βρεις αυτό το discussion σε 850.000 emails.
  00:17:47 - Michael Michelis (Qalzy)
      Α, βασικά μπορεί να το...
  00:17:47 - Speaker 1
      Εδώ είναι που συμφέρει να έχεις ένα AI στο...
  00:17:52 - Michael Michelis (Qalzy)
      Άμα είμαι εγώ σε αυτά τα image, μπορεί να το μπορεί να το κοσμίσω.
  00:18:06 - Speaker 1
      Έχει και αυτό το Gemini εδώ που πληρώνεις έξτρα τον Google να βάλεις στα email σου Α, δε χάτσε Δεν θέλει, ναι, αυτοί είναι το αυτοί του από πάντα Όχι, το Gemini να δούμε μπορεί
  00:18:25 - Michael Michelis (Qalzy)
      Ωραία.    Ωραία.    Ωραία.    Ωραία.    Αυτά τα μοντέλα είναι ότι, άμα έχεις δικό σου χάρνες και χρησιμοποιήσεις τα API's keys, το API usage που σου δίνει το κλοντ, τα 20$, άμα χρησιμοποιούσεις API's είναι γύρω στα 200$-300$.    Κάνανε μία ανάλυση, δεν ξέρω αν το είδες αυτό.    Όλα τα calls εσύ άμα κάνεις το πλάν σου από 20$ plan, τα χρησιμοποιείς.
  00:19:24 - Speaker 1
      Ναι, είναι πολύ περισσότερα κρυμάτα από όταν μαξιμοποιείς το API, ναι, όλοι αυτό λένε, οπότε λέει παίρνω το ProPlan και συνδέω αυτό, αντί να...
  00:19:34 - Michael Michelis (Qalzy)
      Ναι, τώρα πιάνω γιατί η κλοντ δεν σ' αφήνει το προπλάν να πάρεις API key.    Του κόψαμε.    Δεν βρήκε τίποτα.    Σας ευχαριστώ.    Ευχαριστώ.
  00:21:14 - Speaker 1
      Μου έφυξε και η ακριβώς που είναι αυτό, θα ήταν λίγο πιο helpful.
  00:22:01 - Michael Michelis (Qalzy)
      Γκώστη μετσίς, δηλαδή γκώστη μετσίς.
  00:22:02 - Speaker 1
      Κάναμε κάποια συμφωνία σε κάποια φάση to include ghost images if they're available for a certain item.    The only recommended if ghost production images exist to a nuclear leafart of the field recommend under them.    Simon said, replied agreeing to the request.    Ναι, τώρα έχει κάτι ο κώδικας μέσα που λέει ghost images.
  00:22:53 - Michael Michelis (Qalzy)
      Αλλά αυτό το alt one πρέπει να ανταγκώσουμε.
  00:23:35 - Speaker 1
      Δεν μπορώ να βρω, γιατί είναι πάρα πολλά τα τεχειά.    Σίγουρα, κάναμε αυτή τη συμφωνία σε κάποιο λόγο και σε κάποια φάση πιστεύει το AI.    Αλλά, πού ακριβώς, ποιο είναι αυτό το email, το οποίο...
  00:23:48 - Michael Michelis (Qalzy)
      Είναι καλά άμα δεν μπορούμε το βρούμε, εμείς όμως δεν μπορούμε να το βρούμε κι αυτή, σκέψου.
  00:23:53 - Speaker 1
      Ναι, αλλά αυτοί μπορεί να την μου δερφθούν.
  00:23:56 - Michael Michelis (Qalzy)
      Είσαι πολύ αισιόδοξο, σε ακούω.
  00:23:59 - Speaker 1
      Ε, ο Σάιμον που έκανε τη δουλειά, θα θυμάται.    Να, we've only had to bring it.    Currently, we're only sending two images per product.    We can surely include the ghost images.    Today, we had a chance.    Our idea is to send four images instead of the two.    In addition to the main image and alt-1 image, we would include alt-2 and a ghost image.    Do you prefer the images to be sorted in any particular order?    Do you have any preferences regarding the name of the field?    We don't have a strict preference in image order.    It would be best to keep the field names as they are.    The most effective solution would be to include an idea.    Υπότιτλοι AUTHORWAVE 3rd image.
  00:25:08 - Michael Michelis (Qalzy)
      Ωραία.
  00:25:31 - Speaker 1
      Could we confirm that this is consistently the case?    Και δεν βλέπω άλλη απάντηση από τον Σάιμον.    Όχι, δεν υπάρχει άλλη απάντηση μετά από τον Σάιμον.    Υπάρχουν διάφορες κουβέντες με τη Μαρία, Διόνι.    Αλλά δεν νομίζω ότι του είπε αυτή για το field name.    Οπότε κάπου στον κώδικα πρέπει να υπάρχει κάποια λογική όπου παίρνουμε τον ghost image.    Και μετά we fall back to the close-up image, which is likely to be the third one.
  00:26:41 - Michael Michelis (Qalzy)
      Ευχαριστώ.
  00:26:56 - Speaker 1
      Υπότιτλοι AUTHORWAVE Υπότιτλοι AUTHORWAVE    Πιο ίδωμένο στον 12, όπου αποφασίζουμε ποια εικόνα θα χρησιμοποιήσουμε για categorization.    Κάθε υπάρχουν, υπάρχουν rules, που δεν το κάνει ποτέ ο Γιώργος.
  00:27:59 - Michael Michelis (Qalzy)
      Οπότε και για τα similars χρησιμοποιούμε το zero image, το οποίο είναι το alt 1 το zero image.
  00:28:20 - Speaker 1
      Γιατί εδώ λέει, «Our idea is to send four images instead of two, in addition to the main image and alt one, we will include alt two and the ghost image for each problem».    Υπότιτλοι AUTHORWAVE
  00:29:17 - Michael Michelis (Qalzy)
      Άρα το πρόβλημα είναι και ότι το similar job χρησιμοποιεί το full body image.
  00:29:30 - Speaker 1
      σίγουρο, πρόκειται.
  00:29:32 - Michael Michelis (Qalzy)
      Ναι, δε φυγάμε να έχει κανένα και το αστάω Ιώρος.    Και εδώ λέει, «for guess each product has one or two images, never more, in the light catalog».
  00:29:49 - Speaker 1
      Δεν ξέρω, έχουν αλλάξει αυτά τα feeds 850 φορές, δεν ξέρω τι κάνω.    Δηλαδή, η διάλειτη θανότητα είναι ο Γιώργος να μην δίνει ποτέ το καινούριο feed.    Αυτές οι συζητήσεις είναι 17 Μαρτίου.
  00:30:03 - Michael Michelis (Qalzy)
      Ναι, γιατί θέλανε ένα καινούριο φωτιά σε κάποια φάση.
  00:30:13 - Speaker 1
      Ο 18 Μαρτίου έστειλε newly generated registry file, before updating the entire feed.    Και η Διόνη του είπε, ναι, το είδαμε.    και είναι καλό.
  00:30:35 - Michael Michelis (Qalzy)
      Παίζει να μην έχουμε...    Όχι, πρέπει να μην τα έχουμε τα...    Αφού αυτά δείχνουν.    Παίζει να μην έκανε μια σωστή ρηλάχο.
  00:30:47 - Speaker 1
      Για τα 1 Μαρτίου ζήτησε access to platform.    Πριν οι διάμαρτηριότησαν για το quality.    Stop issues το Μάιο.
  00:31:09 - Michael Michelis (Qalzy)
      Ναι, έχουμε δύο ρηλάχοι.    Δεν υπάρχουν εντός ρηλάχοι.    Και ναι, φαίνεται διαφορές, κάτι σαν να δείξω.
  00:31:25 - Speaker 1
      Μετά, εκεί τον Ιούνιο άρχισαν να αποφασίζουν ότι θέλουν να κάνουν όλες αυτές τις ιστορίες που κάνουμε τώρα.
  00:31:27 - Michael Michelis (Qalzy)
      Α, βλέπεις, εμείς έχουμε δύο images.    Συνήθως, όχι όλα, έχουμε, σε 7.000 προϊόντερα έχουμε δύο images και σε 1.600 έχουμε 1 image.    Το alt 1 is the first, so we use that one.    Και προτείνει να αλλάξουμε, να χρησιμοποιήσουμε το alt 2 για clip και similars.
  00:32:04 - Speaker 1
      Και χρησιμοποιούμε εμείς πάντα το one, το zero.
  00:32:07 - Michael Michelis (Qalzy)
      Το ζήραμε.
  00:32:14 - Speaker 1
      Εμένα με ανησυχή ότι είχαμε όλες αυτές τις κουβέντες για να το βελτιώσουμε αυτό.    Αυτό δεν συμβαίνει στο σύστημα μας, οπότε ή αυτοί κάνανε μαλακή.    και δεν μας δώσανε ποτέ το καινούριο feed ή εμείς κάναμε μανάγκια Ήτανε για Similas αρχικά όχι για Soft and Look αρχικά και μετά αποφασίσανε να κάνουνε και Similas και να τα βάλουν όλα και διαμαρτυρώντησαν για το quality δεν θέλανε τίποτα, σταματήσαμε να ασχολούμαστε μαζί τους και μετά ξανά έρθανε πίσω και είπανε θέλουμε Similas, αποφασίσανε το καλέσκο με το API, γουστάκο και μετά ξανά αρχίσανε οι συζητήσεις και μετά πήγε στο widget αυτή η κουβέντα λοιπόν, άκου να δεις
  00:32:27 - Michael Michelis (Qalzy)
      Εγώ πιστεύω ότι αυτές οι συζητήσεις ήταν για το ΣΥΜΙΛΑΣ ή για το ΣΟΠΤΕΛΟΟΥ.
  00:33:19 - Speaker 1
      Αγγένα παιδί πόμαστε, εγώ Λεόνα το πούμε ότι the problem is because we're using the old one whatever image, the basic image, we get two images, currently we only see two images only in the field.    The image that we're using is a full body image and the model cannot identify which item are you referring to, the top or the bottom, and that creates this problem.    We can see there was a conversation in March 2026 that you would be sending where you send a test feed and you said you're going to send additional ghost images.
  00:34:16 - Michael Michelis (Qalzy)
      Ποδάτκο, κοστήματής.
  00:34:17 - Speaker 1
      Ναι, ναι, τι άλλο θα κάνουμε με ghost images.    Did this happen, and what is, are these images in the feed, because we can't see them right now, this is the feed we're using, URL, please compare what those images are there and which feed we should be using.    Γιατί αυτή η κουβέντα έγινε.    Τώρα να πάμε εμείς να κάνουμε update σε ghost στο άλλο image και να βρούμε ότι αυτό το image δεν είναι το σωστό, διότι χρησιμοποιούμε το λάθος feed.    Νομίζω ότι καλύτερα να μας πούνε είστε βλάκες χρησιμοποιείτε το λάθος feed παρά να πάμε εμείς του κεφαλιού μας και μετά να έχουμε προβλήματα.    Μπορεί στην τελική να μην το έκαναν ποτέ update.    Γιατί εγώ βλέπω digital conversation.    Δεν βλέπω συνέχεια στο conversation.    Αυτό το thread, τουλάχιστον.    Η απάντηση διώνει στις 17 Μαρτίου και από εκεί πέρα δεν ξαναπάντησε.    Δες να σου κάνω for word το email για να το βρεις έκορα.    Εγώ αυτό βλέπω σαν τελευταίο.
  00:35:24 - Michael Michelis (Qalzy)
      Αυτό που λες, γιατί έτσι κι αλλιώς εμείς, αφού έχουν τα imagens αυτά, φαίνεται, σε κάποια, να μας πούνε να τα βάλουν σε feed και μετά θα πρέπει να ξανά τρουξουμε.
  00:35:38 - Speaker 1
      Ναι, εγώ νομίζω πήρα να κάνει update-office σε κάποια φάση.    Αλλά μπορεί απλά να το τεστάρανε και να μην το κάνανε live.    Γιατί, σου λέω, σε αυτό το τρέτο conversation φαίνεται να πεθαίνει.    Συνήθως, εσείς μπορούμε να σου κάνουμε refer και στο «This is the last email that we can find» «Where you said you can add those images».    «Have those images being added and where are they».    ΕΛΕΜ σου λέει ότι αυτές τις εικόνες χρησιμοποιούμε ή ότι αυτές οι εικόνες είναι στο feed.
  00:36:16 - Michael Michelis (Qalzy)
      Στο feed υπάρχουν δύο εικόνας, μόνο δύο, ή μία, μπορεί να υπάρχει και μία μόνο, ή δύο.
  00:36:18 - Speaker 1
      Α, υπάρχουν μόνο δύο εικόνες στο feed.    Αυτό θέλω να τσεκάρω ότι μήπως εννοούσε ότι εμείς αυτές χρησιμοποιούμε, αλλά μπορεί στο feed να υπάρχει και παραπάνω για να μην το ξέρουμε.    Αλλά έχει τσεκάρει το, λέτε, εμείς στο feed.    Νομίζω ότι το καλύτερο είναι να σου κάνουμε refers αυτό το email και να σου πούμε, Look, this is because we can't identify which item the image is for.    We have this conversation.    You said you were gonna add the additional images.    Are these images added on the feed?    Let us know where we can find them and we can fix it.
  00:36:59 - Michael Michelis (Qalzy)
      Ναι, καλύτερα, γιατί άμα τα έχουν αυτά τα images, να μας στείλουν έξτρα και να ξαναεξτρέψουμε το job μια εγκαλή.
  00:37:05 - Speaker 1
      Ε, ναι.    Τώρα θα προσπαθούμε να το φτιάξουμε.    δε θα τους αρέσει, θα κάνουμε cycles καλύτερα να το ρίξουμε σε αυτούς για να γίνει σωστά η δουλειά και να σχοληθούμε με κάποια άλλη ζωήτηση Οκ.
  00:37:14 - Michael Michelis (Qalzy)
      Ομαδύστη, ειναι.
  00:37:18 - Speaker 1
      Κουλ.    Bye.

