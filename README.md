# Poetry-Generation-in-Urdu

You will use n-gram language modeling to generate some poetry using the spaCy library for
text processing. For the purpose of this assignment a poem will consist of three stanzas each containing four
verses where each verse consists of 7—10 words. For example, following is a manually generated stanza.
دل سے نکال یاس کہ زندہ ہوں میں ابھی،
ہوتا ہے کیوں اداس کہ زندہ ہوں میں ابھی،
مایوسیوں کی قید سے خود کو نکال کر،
آ جاؤ میرے پاس کہ زندہ ہوں میں ابھی،
آ کر کبھی تو دید سے سیراب کر مجھے،
مرتی نہیں ہے پیاس کہ زندہ ہوں میں ابھی،
مہر و وفا خلوص و محبت گداز دل،
سب کچھ ہے میرے پاس کہ زندہ ہوں میں ابھی،
لوٹیں گے تیرے آتے ہی پھر دن بہار کے،
رہتی ہے دل میں آس کہ زندہ ہوں میں،
نایابؔ شاخ چشم میں کھلتے ہیں اب بھی خواب،
سچ ہے ترا قیاس کہ زندہ ہوں میں ابھی
The task is to print three such stanzas with an empty line in between. The generational model can be trained
on the provided Poetry Corpus containing poems from Faiz, Ghalib and Iqbal. You will train unigram and
bigram models using this corpus. These models will be used to generate poetry. Several online solutions are
available for English that use the NLTK library. However, we will be using the spaCy library to accomplish this
task!
