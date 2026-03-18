<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grammar & Philosophy: The Canvas of Leo</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.8; color: #2c3e50; max-width: 900px; margin: 0 auto; padding: 40px; background-color: #f4f7f9; }
        .container { background: white; padding: 40px; border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); }
        
        h1, h2 { color: #1a73e8; border-bottom: 2px solid #e1e4e8; padding-bottom: 10px; }
        
        /* Word Bank */
        .word-bank { background: #fff; border: 2px dashed #1a73e8; padding: 20px; border-radius: 10px; margin-bottom: 30px; display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; }
        .word { padding: 5px 15px; background: #e8f0fe; border-radius: 20px; font-weight: 600; color: #1a73e8; transition: all 0.3s; }
        .used { text-decoration: line-through; opacity: 0.3; background: #f1f3f4; color: #9aa0a6; }

        /* Story Area */
        .story { font-size: 1.15rem; text-align: justify; margin-bottom: 40px; }
        input { border: none; border-bottom: 2px solid #bdc3c7; width: 170px; padding: 2px; text-align: center; font-size: 1.05rem; font-family: inherit; color: #1a73e8; cursor: pointer; transition: 0.3s; }
        input:focus { outline: none; border-bottom-color: #1a73e8; background: #f8fbff; }
        .correct { background-color: #e6ffed !important; border-bottom-color: #28a745 !important; color: #28a745; font-weight: bold; }

        /* Philosophy Section */
        .philosophy { background: #fff8e1; padding: 30px; border-radius: 10px; border-left: 5px solid #ffc107; margin-top: 50px; }
        .q-box { margin-bottom: 20px; }
        .q-box strong { color: #856404; display: block; margin-bottom: 5px; }

        .btn-reset { background: #1a73e8; color: white; border: none; padding: 10px 25px; border-radius: 5px; cursor: pointer; font-weight: bold; margin-top: 20px; }
        .btn-reset:hover { background: #1557b0; }
        .tip { font-size: 0.9rem; color: #70757a; font-style: italic; margin-bottom: 15px; }
    </style>
</head>
<body>

<div class="container">
    <h1>The Canvas of Leo</h1>
    <p class="tip">Instructions: Type the correct form. If you are stuck, <strong>click the box</strong> to reveal the answer.</p>

    <div class="word-bank">
        <span class="word" id="w1">struggle</span> <span class="word" id="w2">rise</span> <span class="word" id="w3">organize</span> 
        <span class="word" id="w4">prepare</span> <span class="word" id="w5">consider</span> <span class="word" id="w6">play</span> 
        <span class="word" id="w7">sit</span> <span class="word" id="w8">stack</span> <span class="word" id="w9">find</span> 
        <span class="word" id="w10">experience</span> <span class="word" id="w11">walk</span> <span class="word" id="w12">fill</span> 
        <span class="word" id="w13">paint</span> <span class="word" id="w14">seek</span> <span class="word" id="w15">know</span> 
        <span class="word" id="w16">hand out</span> <span class="word" id="w17">cloud</span> <span class="word" id="w18">not define</span> 
        <span class="word" id="w19">view</span> <span class="word" id="w20">begin</span>
    </div>

    <div class="story">
        In the quiet suburbs, seventeen-year-old Leo 
        <strong>(1)</strong> <input type="text" data-ans="is struggling" data-word="w1" onclick="reveal(this)"> 
        with his identity. Every morning, as the sun 
        <strong>(2)</strong> <input type="text" data-ans="rises" data-word="w2" onclick="reveal(this)"> 
        over the rooftops, Leo’s life 
        <strong>(3)</strong> <input type="text" data-ans="is organized" data-word="w3" onclick="reveal(this)"> 
        by his father. Currently, Leo 
        <strong>(4)</strong> <input type="text" data-ans="is preparing" data-word="w4" onclick="reveal(this)"> 
        for medical school entrance exams.
        <br><br>
        "Medicine 
        <strong>(5)</strong> <input type="text" data-ans="is considered" data-word="w5" onclick="reveal(this)"> 
        a stable career," his father says. While his peers 
        <strong>(6)</strong> <input type="text" data-ans="are playing" data-word="w6" onclick="reveal(this)"> 
        football, Leo 
        <strong>(7)</strong> <input type="text" data-ans="is sitting" data-word="w7" onclick="reveal(this)"> 
        at a desk where thick textbooks 
        <strong>(8)</strong> <input type="text" data-ans="are stacked" data-word="w8" onclick="reveal(this)"> 
        high. However, sketches 
        <strong>(9)</strong> <input type="text" data-ans="are found" data-word="w9" onclick="reveal(this)"> 
        hidden in his biology notes.
        <br><br>
        Lately, a strange shift 
        <strong>(10)</strong> <input type="text" data-ans="is being experienced" data-word="w10" onclick="reveal(this)"> 
        by Leo. Today, instead of studying, he 
        <strong>(11)</strong> <input type="text" data-ans="is walking" data-word="w11" onclick="reveal(this)"> 
        toward the local arts center. Inside, the air 
        <strong>(12)</strong> <input type="text" data-ans="is filled" data-word="w12" onclick="reveal(this)"> 
        with the scent of turpentine. A large mural 
        <strong>(13)</strong> <input type="text" data-ans="is being painted" data-word="w13" onclick="reveal(this)"> 
        by a group of local artists nearby.
        <br><br>
        "You look like someone who 
        <strong>(14)</strong> <input type="text" data-ans="is seeking" data-word="w14" onclick="reveal(this)"> 
        a spark," a voice says. It’s Sarah. She 
        <strong>(15)</strong> <input type="text" data-ans="knows" data-word="w15" onclick="reveal(this)"> 
        talent. Right now, brushes 
        <strong>(16)</strong> <input type="text" data-ans="are being handed out" data-word="w16" onclick="reveal(this)"> 
        out to a new class.
        <br><br>
        The anxiety that usually 
        <strong>(17)</strong> <input type="text" data-ans="clouds" data-word="w17" onclick="reveal(this)"> 
        his mind begins to lift. Identity 
        <strong>(18)</strong> <input type="text" data-ans="is not defined" data-word="w18" onclick="reveal(this)"> 
        by others. Although the path ahead 
        <strong>(19)</strong> <input type="text" data-ans="is viewed" data-word="w19" onclick="reveal(this)"> 
        as uncertain, Leo finally feels at peace. He 
        <strong>(20)</strong> <input type="text" data-ans="is beginning" data-word="w20" onclick="reveal(this)"> 
        to understand that his life is his own masterpiece.
    </div>

    <button class="btn-reset" onclick="location.reload()">Reset Exercise</button>

    <div class="philosophy">
        <h2>Philosophical Discussion</h2>
        <div class="q-box">
            <strong>1. Discovery vs. Creation:</strong> Is identity something "found" inside us (Essentialism) or something we "create" through action (Existentialism)?
        </div>
        <div class="q-box">
            <strong>2. The Social Mirror:</strong> Can we truly define ourselves if the people around us refuse to see us that way?
        </div>
        <div class="q-box">
            <strong>3. The Ethics of Duty:</strong> Does an individual have a moral obligation to fulfill family expectations over personal passion?
        </div>
        <div class="q-box">
            <strong>4. Identity in Flux:</strong> If identity is always "becoming" (Present Continuous), is it ever a fixed destination?
        </div>
        <div class="q-box">
            <strong>5. Environmental Self:</strong> How much of Leo's "true self" was triggered by the physical tools and scents of the art center?
        </div>
    </div>
</div>

<script>
    function reveal(el) {
        if (el.value.toLowerCase() !== el.dataset.ans.toLowerCase()) {
            el.value = el.dataset.ans;
            el.classList.add('correct');
            document.getElementById(el.dataset.word).classList.add('used');
        }
    }

    document.querySelectorAll('input').forEach(input => {
        input.addEventListener('input', function() {
            if (this.value.trim().toLowerCase() === this.dataset.ans.toLowerCase()) {
                this.classList.add('correct');
                document.getElementById(this.dataset.word).classList.add('used');
            }
        });
    });
</script>

</body>
</html>
