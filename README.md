# Abey

{
    "frames": {
        "exit-survey": {
            "kind": "exp-lookit-exit-survey",
            "debriefing": {
                "text": "Here is where you would enter debriefing information for the family. This is a chance to explain the purpose of your study and how the family helped; at this point it's more obvious to the participant that skimming the info is fine if they're not super-interested, so you can elaborate in ways you might have avoided ahead of time in the interest of keeping instructions short. You may want to mention the various conditions kids were assigned to if you didn't before, and try to head off any concerns parents might have about how their child 'did' on the study, especially if there are 'correct' answers that will have been obvious to a parent. <br><br> It is great if you can link people to a layperson-accessible article on a related topic - e.g., media coverage of one of your previous studies in this research program, a talk on Youtube, a parenting resource. <br><br> If you are compensating participants, restate what the compensation is (and any conditions, and let them know when to expect their payment! E.g.: To thank you for your participation, we'll be emailing you a $4 Amazon gift card - this should arrive in your inbox within the next week after we confirm your consent video and check that your child is in the age range for this study. (If you don't hear from us by then, feel free to reach out!) If you participate again with another child in the age range, you'll receive one gift card per child.",
                "title": "Thank you!"
            }
        },
        "instructions": {
            "kind": "exp-lookit-instructions",
            "blocks": [
                {
                    "title": "Overview of how to participate in this study",
                    "listblocks": [
                        {
                            "text": "In this study your child will listen to illustrated stories about a Bear named Bobo!"
                        },
                        {   "text": "There are 8 stories. Your child will see 3 pages of each story and asked to choose an ending to each story afterwards."

                        },
                        {
                            "text": "See https://lookit.github.io/ember-lookit-frameplayer/classes/ExpLookitInstructions.html"
                        },
                        {
                            "text": "You can display any text, audio, images, and video you want, and can optionally require participants to play audio/video segments to move on. You can also choose whether to display the webcam."
                        }
                    ]
                },
                {
                    "title": "Adjust your speakers",
                    "text": "Please try playing this sample audio to make sure you'll be able to hear the story.",
                    "mediaBlock": {
                        "text": "You should hear 'Ready to go?'",
                        "isVideo": false,
                        "sources": [
                            {
                                "src": "https://s3.amazonaws.com/lookitcontents/exp-physics-final/audio/ready.mp3",
                                "type": "audio/mp3"
                            },
                            {
                                "src": "https://s3.amazonaws.com/lookitcontents/exp-physics-final/audio/ready.ogg",
                                "type": "audio/ogg"

                            }
                        ],
                        "mustPlay": true,
                        "warningText": "Please try playing the sample audio."
                    }
                }
            ],
            "showWebcam": true,
            "webcamBlocks": [
                {
                    "title": "Make sure we can see you",
                    "listblocks": [
                        {
                            "text": "Take a look at your webcam view above. Get comfy, and adjust your own position or the computer as needed so both you and your child are visible."
                        },
                        {
                            "text": "This isn't a Skype call - no one in the lab can see you - but the recorded video of your participation will be sent to the lab to help with data analysis. It's helpful for us to be able to see if your child was pointing or looking confused, for example."
                        }
                    ]
                }
            ],
            "nextButtonText": "Next"
        },
        "video-config": {
            "kind": "exp-video-config",
            "troubleshootingIntro": "This is a standard frame you probably want to put at the very start of your study. You can customize this bit of text; the rest is standard and maintained by Lookit."
        },
        "video-consent": {
            "kind": "exp-lookit-video-consent",
            "template": "consent_005",
            "PIName": "Lookit Tutorial Participant",
            "PIContact": "Jane Smith at (123) 456-7890",
            "include_databrary": true,
            "risk_statement": "There are no expected risks to participation.",
            "datause": "We are interested in how your child uses statistical evidence to figure out the cause of an event. A research assistant will watch your video and mark down your child's answer to the question at the end of the story, and as well as other information such as interactions between you and your child during the story.",
            "payment": "After you finish the study, we will email you a $5 BabyStore gift card within approximately three days. To be eligible for the gift card your child must be in the age range for this study, you need to submit a valid consent statement, and we need to see that there is a child with you. But we will send a gift card even if you do not finish the whole study or we are not able to use your child's data! There are no other direct benefits to you or your child from participating, but we hope you will enjoy the experience.",
            "purpose": "This study is about how children use statistical information to adjust their beliefs about cause and effect.",
            "procedures": "In this study you child will view a digital 'storybook' about Bunny, who sometimes gets a tummyache. Each day Bunny eats different foods and does different activities, and we hear whether she gets a tummyache. Sometimes, Bunny feels scared because of show-and-tell. We are interested in how the pattern of evidence influences your child's beliefs about what causes Bunny's tummyache. We will ask you (the parent) to avoid discussing why Bunny has a tummyache until the end of the study. There are no anticipated risks associated with participating.",
            "institution": "Science University"
        },
        
        "storybook-causal-female": {
            "kind": "group",
            "frameList": [
                {
                    "audio": "Sandwich-3her",
                    "images": [
                        {
                            "id": "storybookIllustration",
                            "src": "Painting-1.png",
                            "top": 0,
                            "left": 10,
                            "width": 80
                        }
                    ]
                },
                {
                    "audio": "Sandwich-3her",
                    "images": [
                        {
                            "id": "storybookIllustration",
                            "src": "Bobo.png",
                            "top": 0,
                            "left": 10,
                            "width": 80
                        }
                    ]
                }
            ],
            "commonFrameProperties": {
                "kind": "exp-lookit-images-audio",
                "baseDir": "https://raw.githubusercontent.com/zozden/lookit-stimuli-template/master/",
                "id": "storybook-group",
                "audioTypes": [
                    "mp3",
                    "ogg"
                ],
                "autoProceed": false,
                "doRecording": false,
                "parentTextBlock": {
                    "css": {
                        "font-size": "1.5em"
                    },
                    "text": "Please help keep your child's attention, but don't talk with him or her about WHY Bunny might be getting a tummyache yet! Feel free to replay the audio if your child was distracted.",
                    "title": "For parents"
                }
            }
        },
        "storybook-causal-male": {
            "kind": "group",
            "frameList": [
                {
                    "audio": "Sandwich-3his",
                    "images": [
                        {
                            "id": "storybookIllustration",
                            "src": "BigBear.png",
                            "top": 0,
                            "left": 10,
                            "width": 80

                        }
                    ]
                },
                {
                    "audio": "Sandwich-3his",
                    "images": [
                        {
                            "id": "storybookIllustration",
                            "src": "BearsAll.png",
                            "top": 0,
                            "left": 10,
                            "width": 80
                        }
                    ]
                }
            ],
            "commonFrameProperties": {
                "kind": "exp-lookit-images-audio",
                "baseDir": "https://raw.githubusercontent.com/zozden/lookit-stimuli-template/master/",
                "id": "storybook-group",
                "audioTypes": [
                    "mp3",
                    "ogg"
                ],
                "autoProceed": false,
                "doRecording": false,
                "parentTextBlock": {
                    "css": {
                        "font-size": "1.5em"
                    },
                    "text": "Please help keep your child's attention, but don't talk with him or her about WHY Bunny might be getting a tummyache yet! Feel free to replay the audio if your child was distracted.",
                    "title": "For parents"
                }
            }
        }
    },


    "sequence": [
        "instructions",
        "storybook-causal-male",
        "storybook-causal-female",
        "video-consent",
        "exit-survey",
        "video-config"

    ]
}
