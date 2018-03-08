<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name=viewport content="width=device-width, initial-scale=1">
    <title>D&D 5e quick reference</title>
    <!-- CSS -->
    <link rel="stylesheet" type="text/css" href="css/quickref.css">
    <link rel="stylesheet" type="text/css" href="css/icons.css">
    <!-- Fonts -->
    <link href='https://fonts.googleapis.com/css?family=Noto+Sans:400,700,400italic,700italic' rel='stylesheet' type='text/css'>
    <link href='https://fonts.googleapis.com/css?family=Lora:700' rel='stylesheet' type='text/css'>
    <!-- Javascript -->
    <script type="text/javascript" src="js/jquery/jquery.min.js" charset="utf-8"></script>
</head>
<body class="page-background">
    <div class="page fontsize" data-size="fullscreen">

        <!-- Movement section -->
        <div id="section-movement" class="section-container">
            <div class="section-title">
                Movement <span class="float-right">limited by movement speed</span>
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    You can move at any time during your turn (before, after, or during actions).
                </div>
                <div class="section-row" id="basic-movement">
                </div>
            </div>
        </div>
 
        <!-- Action section -->
        <div id="section-action" class="section-container">
            <div class="section-title">
                Action <span class="float-right">1/turn</span>
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    You can also interact with one object or feature of the
                    environment for free.
                </div>
                <div class="section-row" id="basic-actions"></div>
            </div>
        </div>

        <!-- Bonus action section -->
        <div id="section-bonus-action" class="section-container">
            <div class="section-title">
                Bonus action <span class="float-right">max. 1/turn</span>
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    You can take a bonus action only when a special ability, spell, or feature
                    states that you can do something as a bonus action.
                </div>
                <div class="section-row" id="basic-bonus-actions"></div>
            </div>
        </div>

        <!-- Reaction section -->
        <div id="section-reaction" class="section-container">
            <div class="section-title">
                Reaction <span class="float-right">max. 1/round</span>
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    A reaction is an instant response to a trigger of some kind, which
                    can occur on your turn or on someone else's.
                </div>
                <div class="section-row" id="basic-reactions"></div>
            </div>
        </div>

        <!-- Condition section -->
        <div id="section-condition" class="section-container">
            <div class="section-title">
                Condition
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    Conditions alter your capabilities in a variety of ways, and can arise as a result of a spell, a class feature, a monster's attack, or other effect.
                </div>
                <div class="section-row" id="basic-conditions"></div>
            </div>
        </div>
        
        <!-- Environmental section -->
        <div id="section-environment" class="section-container">
            <div class="section-title">
                Environmental Effects
            </div>
            <div class="section-content">
                <div class="section-row section-subtitle text fontsize">
                    Effects that obscure vision can prove a significant hindrance to most adventuring tasks.
                </div>
                <div class="section-row" id="environment-obscurance"></div>
                <div class="section-row section-subtitle text fontsize">
                    The presence or absence of light in an environment creates three categories of illumination.
                </div>
                <div class="section-row" id="environment-light"></div>
                <div class="section-row section-subtitle text fontsize">
                    Some creatures have extraordinary senses that allow them to perceive their environment.
                </div>
                <div class="section-row" id="environment-vision"></div>
                <div class="section-row section-subtitle text fontsize">
                    Obstacles can provide cover during combat, making a target more difficult to harm.
                </div>
                <div class="section-row" id="environment-cover"></div>
            </div>
        </div>

    </div>

    <!-- Modal -->
    <div class="modal" id="modal" tabindex="-1">
        <div class="modal-backdrop" id="modal-backdrop"></div>
        <div class="modal-dialog modalsize">
            <div class="section-container modal-container" id="modal-container">
                <div class="section-title" id="modal-title">
                    Modal title<span class="float-right">Action</span>
                </div>
                <div class="section-content">
                    <div class="section-row section-subtitle text" id="modal-subtitle">
                        Subtitle
                    </div>
                    <div class="section-row text">
                        <div id="modal-bullets">
                        </div>
                    </div>
                    <div class="section-row text" id="modal-reference">
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Data -->
    <script type="text/javascript" src="js/data_movement.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/data_action.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/data_bonusaction.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/data_reaction.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/data_condition.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/data_environment.js" charset="utf-8"></script>
    <script type="text/javascript" src="js/quickref.js" charset="utf-8"></script>
</body>
</html>
