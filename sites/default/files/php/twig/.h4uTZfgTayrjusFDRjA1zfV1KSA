<?php

use Twig\Environment;
use Twig\Error\LoaderError;
use Twig\Error\RuntimeError;
use Twig\Extension\SandboxExtension;
use Twig\Markup;
use Twig\Sandbox\SecurityError;
use Twig\Sandbox\SecurityNotAllowedTagError;
use Twig\Sandbox\SecurityNotAllowedFilterError;
use Twig\Sandbox\SecurityNotAllowedFunctionError;
use Twig\Source;
use Twig\Template;

/* themes/custom/barriotestamptheme/templates/page.html.twig */
class __TwigTemplate_17ec731442d098796fe5e0258f8c8cce795cd5e127952e58d42faf9747876003 extends \Twig\Template
{
    private $source;
    private $macros = [];

    public function __construct(Environment $env)
    {
        parent::__construct($env);

        $this->source = $this->getSourceContext();

        $this->parent = false;

        $this->blocks = [
        ];
        $this->sandbox = $this->env->getExtension('\Twig\Extension\SandboxExtension');
        $tags = array("if" => 48);
        $filters = array("escape" => 45, "render" => 54);
        $functions = array();

        try {
            $this->sandbox->checkSecurity(
                ['if'],
                ['escape', 'render'],
                []
            );
        } catch (SecurityError $e) {
            $e->setSourceContext($this->source);

            if ($e instanceof SecurityNotAllowedTagError && isset($tags[$e->getTagName()])) {
                $e->setTemplateLine($tags[$e->getTagName()]);
            } elseif ($e instanceof SecurityNotAllowedFilterError && isset($filters[$e->getFilterName()])) {
                $e->setTemplateLine($filters[$e->getFilterName()]);
            } elseif ($e instanceof SecurityNotAllowedFunctionError && isset($functions[$e->getFunctionName()])) {
                $e->setTemplateLine($functions[$e->getFunctionName()]);
            }

            throw $e;
        }

    }

    protected function doDisplay(array $context, array $blocks = [])
    {
        $macros = $this->macros;
        // line 41
        echo "<div class=\"layout-wrapper\">
<div class=\"layout-container\">

  <header role=\"banner\">
    ";
        // line 45
        echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "header", [], "any", false, false, true, 45), 45, $this->source), "html", null, true);
        echo "
  </header>

  ";
        // line 48
        if (twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "primary_menu", [], "any", false, false, true, 48)) {
            // line 49
            echo "    <div id=\"menu\">
    ";
            // line 50
            echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "primary_menu", [], "any", false, false, true, 50), 50, $this->source), "html", null, true);
            echo "
    </div>
  ";
        }
        // line 53
        echo "
  ";
        // line 54
        if ( !twig_test_empty($this->extensions['Drupal\Core\Template\TwigExtension']->renderVar(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "breadcrumb", [], "any", false, false, true, 54)))) {
            // line 55
            echo "    <div id=\"breadcrumb\">
    ";
            // line 56
            echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "breadcrumb", [], "any", false, false, true, 56), 56, $this->source), "html", null, true);
            echo "
    </div>
  ";
        }
        // line 59
        echo "
  <main role=\"main\">
    <div class=\"main-outer\">
    <div class=\"main-inner\">
    <a id=\"main-content\" tabindex=\"-1\"></a>";
        // line 64
        echo "
    <div class=\"layout-content\">
      ";
        // line 66
        echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "content", [], "any", false, false, true, 66), 66, $this->source), "html", null, true);
        echo "
    </div>";
        // line 68
        echo "
    ";
        // line 69
        if (twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "sidebar_first", [], "any", false, false, true, 69)) {
            // line 70
            echo "      <aside class=\"layout-sidebar-first\" role=\"complementary\">
        ";
            // line 71
            echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "sidebar_first", [], "any", false, false, true, 71), 71, $this->source), "html", null, true);
            echo "
      </aside>
    ";
        }
        // line 74
        echo "
    ";
        // line 75
        if (twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "sidebar_second", [], "any", false, false, true, 75)) {
            // line 76
            echo "      <aside class=\"layout-sidebar-second\" role=\"complementary\">
        ";
            // line 77
            echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "sidebar_second", [], "any", false, false, true, 77), 77, $this->source), "html", null, true);
            echo "
      </aside>
    ";
        }
        // line 80
        echo "    </div>
    </div>
  </main>

  ";
        // line 84
        if (twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "footer", [], "any", false, false, true, 84)) {
            // line 85
            echo "    <footer role=\"contentinfo\">
      ";
            // line 86
            echo $this->extensions['Drupal\Core\Template\TwigExtension']->escapeFilter($this->env, $this->sandbox->ensureToStringAllowed(twig_get_attribute($this->env, $this->source, ($context["page"] ?? null), "footer", [], "any", false, false, true, 86), 86, $this->source), "html", null, true);
            echo "
    </footer>
  ";
        }
        // line 89
        echo "
</div>";
        // line 91
        echo "</div>";
    }

    public function getTemplateName()
    {
        return "themes/custom/barriotestamptheme/templates/page.html.twig";
    }

    public function isTraitable()
    {
        return false;
    }

    public function getDebugInfo()
    {
        return array (  161 => 91,  158 => 89,  152 => 86,  149 => 85,  147 => 84,  141 => 80,  135 => 77,  132 => 76,  130 => 75,  127 => 74,  121 => 71,  118 => 70,  116 => 69,  113 => 68,  109 => 66,  105 => 64,  99 => 59,  93 => 56,  90 => 55,  88 => 54,  85 => 53,  79 => 50,  76 => 49,  74 => 48,  68 => 45,  62 => 41,);
    }

    public function getSourceContext()
    {
        return new Source("", "themes/custom/barriotestamptheme/templates/page.html.twig", "C:\\xampp\\htdocs\\amp-drupal\\themes\\custom\\barriotestamptheme\\templates\\page.html.twig");
    }
}
