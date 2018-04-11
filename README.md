# KeyboardBehavior

KeyboardBehavior can notify you the changes of soft keyboard's visibility!

##Usage

KeyboardBehavior.getInstance(this).addListener(new KeyboardBehavior.KBehave() {
    @Override
    void onToggle(boolean visible) {
        Log.i("wbq", String.format("soft keyboard is %s", visible ? "visible" : "invisible"));
    }
});
